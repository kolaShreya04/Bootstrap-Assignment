# Bootstrap-Assignment
<!doctype html>
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.6.2/dist/css/bootstrap.min.css" integrity="sha384-xOolHFLEh07PJGoPkLv1IbcEPTNtaed2xpHsD9ESMhqIYd0nLMwNLD69Npy4HI+N" crossorigin="anonymous">

    <title>Bootstrap-Assignment</title>
  </head>
  <body>
     <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <a class="navbar-brand" href="#">Bootstrap</a>
  </nav>

  <div class="container mt-4">
      <div class="card">
      <div class="card-body">
        <h5 class="card-title">Card Title</h5>
        <p class="card-text">This is some random card content. Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
        <button class="btn btn-primary">Learn More</button>
      </div>
    </div>

    <button type="button" class="btn btn-success mt-3" data-toggle="modal" data-target="#myModal">
      Open Modal
    </button>

    <div class="modal fade" id="myModal">
      <div class="modal-dialog">
        <div class="modal-content">
          <div class="modal-header">
            <h5 class="modal-title">Modal Title</h5>
            <button type="button" class="close" data-dismiss="modal">&times;</button>
          </div>
          <div class="modal-body">
            This is some random modal content. Lorem ipsum dolor sit amet, consectetur adipiscing elit.
          </div>
          <div class="modal-footer">
            <button type="button" class="btn btn-secondary" data-dismiss="modal">Close</button>
            <button type="button" class="btn btn-primary">Save changes</button>
          </div>
        </div>
      </div>
    </div>
  </div>
  </body>
</html> 
