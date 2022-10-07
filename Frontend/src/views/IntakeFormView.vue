<template>
    <div class="row justify-content-center">
        <div class="col-md-6">
            <h3 class="text-center">Client Intake Form</h3>
            <form @submit.prevent="handleSubmitForm">
                <div class="form-group required">
                    <label>Company Name</label>
                    <input type="text" class="form-control" required>
                </div>
                <div class="form-group">
                    <label>Location Name(DBA)</label>
                    <input type="text" class="form-control" required>
                </div>
                <div class="form-group required">
                    <label>Business Email Address</label>
                    <input type="text" class="form-control" required>
                </div>
                <div class="form-group">
                    <label>Location Address</label>
                    <input type="text" class="form-control" required>
                </div>
                <div class="form-group required">
                    <label>Location City</label>
                    <input type="text" class="form-control" required>
                </div>
                <div class="form-group required">
                    <label>Location County</label>
                    <input type="text" class="form-control" required>
                </div>
                <div class="form-group required">
                    <label>Mailing Address</label>
                    <input type="text" class="form-control" required>
                </div>
                <div class="form-group required">
                    <label>Business Phone Number</label>
                    <input type="text" class="form-control" required>
                </div>
                <div class="form-group required">
                    <label>Alcohol Permit</label>
                    <select class="form-select" required aria-label="Default select example">
                        <option selected disabled value="">Select Alcohol Permit Type</option>
                        <option>P</option>
                        <option>Q</option>
                        <option>BQ</option>
                        <option>BG</option>
                    </select>
                </div>
                <div class="form-group required">
                    <label>EIN</label>
                    <input type="text" class="form-control" required>
                </div>
                <div class="form-group required">
                    <label>Purchase Price</label>
                    <input type="text" class="form-control" required>
                </div>
                <div class="form-group required">
                    <label>Purchase Date</label>
                    <input type="text" class="form-control" required>
                </div>
                <div class="form-group required">
                    <label>First Date of Operation</label>
                    <input type="text" class="form-control" required>
                </div>
                <div class="form-group required">
                    <label>EIN</label>
                    <input type="text" class="form-control" required>
                </div>
                <button class="btn btn-success mt-3">Create</button>
            </form>
        </div>
    </div>
</template>

<script>

</script>

<style>
    .table {
        text-align: center;
    }
    .btn-items{
        text-align: center;
    }
</style>