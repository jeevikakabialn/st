# st

@model YourNamespace.YourModel

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Registration Form</title>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css">
</head>
<body>
    <div class="container">
        <div class="row justify-content-center mt-5">
            <div class="col-md-8">
                <div class="card">
                    <div class="card-header">
                        <h3>Registration</h3>
                    </div>
                    <div class="card-body">
                        <form asp-action="Register" method="post">
                            <h5>Personal Details</h5>
                            <div class="form-row">
                                <div class="form-group col-md-6">
                                    <label for="FullName">Full Name</label>
                                    <input type="text" class="form-control" id="FullName" name="FullName" required />
                                </div>
                                <div class="form-group col-md-6">
                                    <label for="DateOfBirth">Date of Birth</label>
                                    <input type="date" class="form-control" id="DateOfBirth" name="DateOfBirth" required />
                                </div>
                            </div>
                            <div class="form-row">
                                <div class="form-group col-md-6">
                                    <label for="Email">Email</label>
                                    <input type="email" class="form-control" id="Email" name="Email" required />
                                </div>
                                <div class="form-group col-md-6">
                                    <label for="MobileNumber">Mobile Number</label>
                                    <input type="text" class="form-control" id="MobileNumber" name="MobileNumber" required />
                                </div>
                            </div>
                            <div class="form-row">
                                <div class="form-group col-md-6">
                                    <label for="Gender">Gender</label>
                                    <input type="text" class="form-control" id="Gender" name="Gender" required />
                                </div>
                                <div class="form-group col-md-6">
                                    <label for="Occupation">Occupation</label>
                                    <input type="text" class="form-control" id="Occupation" name="Occupation" />
                                </div>
                            </div>

                            <h5>Identity Details</h5>
                            <div class="form-row">
                                <div class="form-group col-md-6">
                                    <label for="IDType">ID Type</label>
                                    <input type="text" class="form-control" id="IDType" name="IDType" required />
                                </div>
                                <div class="form-group col-md-6">
                                    <label for="IDNumber">ID Number</label>
                                    <input type="text" class="form-control" id="IDNumber" name="IDNumber" required />
                                </div>
                            </div>
                            <div class="form-row">
                                <div class="form-group col-md-6">
                                    <label for="IssueAuthority">Issue Authority</label>
                                    <input type="text" class="form-control" id="IssueAuthority" name="IssueAuthority" required />
                                </div>
                                <div class="form-group col-md-6">
                                    <label for="IssueDate">Issue Date</label>
                                    <input type="date" class="form-control" id="IssueDate" name="IssueDate" required />
                                </div>
                            </div>
                            <div class="form-row">
                                <div class="form-group col-md-6">
                                    <label for="IssueState">Issue State</label>
                                    <input type="text" class="form-control" id="IssueState" name="IssueState" required />
                                </div>
                                <div class="form-group col-md-6">
                                    <label for="ExpiryDate">Expiry Date</label>
                                    <input type="date" class="form-control" id="ExpiryDate" name="ExpiryDate" required />
                                </div>
                            </div>
                            
                            <button type="submit" class="btn btn-primary btn-block">Next</button>
                        </form>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <script src="https://code.jquery.com/jquery-3.2.1.slim.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.11.0/umd/popper.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/js/bootstrap.min.js"></script>
</body>
</html>
csssss
/* Optional additional styling */
body {
    background-color: #f4f7fc;
}

.card-header {
    text-align: center;
    font-weight: bold;
}

<script src="https://code.jquery.com/jquery-3.2.1.slim.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.11.0/umd/popper.min.js"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/js/bootstrap.min.js"></script>
