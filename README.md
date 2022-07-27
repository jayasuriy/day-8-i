# day-8-i
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.5.3/dist/css/bootstrap.min.css">

    <style>
        .my-container {
            background-color: rgb(221, 235, 145);
        }
    </style>
</head>

<body>

    <div class="container my-container p-4">
        <div class="row ">
            <div class="col-6 offset-3 bg-danger">
                <div class="row">
                    <div class="col-6">
                        <div class="form-group">
                            <label for="first-name">First Name</label>
                            <input id="first-name" class="form-control" type="text" name="first-name">
                        </div>
                    </div>
                    <div class="col-6 order-md-first">
                        <div class="form-group">
                            <label for="last-name">Last Name</label>
                            <input id="last-name" class="form-control" type="text" name="last-name">
                        </div>
                    </div>
                </div>


                <div class="form-group">
                    <label for="email">Email</label>
                    <input id="email" class="form-control" type="email" name="email">
                </div>
                <div class="form-group">
                    <label for="mobile">Mobile</label>
                    <input id="mobile" class="form-control" type="text" name="mobile">
                </div>
                <div class="row">
                    <div class="col-6">
                        <div class="form-group">
                            <label for="address-1">Address Line 1</label>
                            <input id="address-1" class="form-control" type="text" name="address-1">
                        </div>
                    </div>
                    <div class="col-6">
                        <div class="form-group">
                            <label for="address-2">Address Line 2</label>
                            <input id="address-2" class="form-control" type="text" name="address-2">
                        </div>
                    </div>
                </div>
                <div class="row">
                    <div class="col-6">
                        <div class="form-group">
                            <label for="district">District</label>
                            <select name="district" id="district" class="custom-select">
                                <option value="CH">Chennai</option>
                                <option value="CBE">Coimbatore</option>
                            </select>
                        </div>
                    </div>
                    <div class="col-6 order-sm-first">
                        <div class="form-group">
                            <label for="state">state</label>
                            <select name="state" id="state" class="custom-select">
                                <option value="TN">Tamil Nadu</option>
                                <option value="KA">Karnataka</option>
                            </select>
                        </div>
                    </div>
                </div>
                <button class="btn btn-primary btn-block">Submit</button>
            </div>
        </div>
    </div>


    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@4.5.3/dist/js/bootstrap.bundle.min.js"></script>

</body>

</html>
