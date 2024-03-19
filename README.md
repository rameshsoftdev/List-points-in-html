# List-points-in-html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Service List</title>
  <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
  <style>
    .service-list {
      list-style: none;
      padding: 0;
    }

    .service-list-item {
      position: relative;
      padding-left: 30px;
    }

    .service-list-item::before {
      content: "";
      position: absolute;
      top: 8px;
      left: 0;
      width: 16px;
      height: 16px;
      border-radius: 50%;
      background-color: #28a745; /* green color */
    }

    .service-list-item::after {
      content: "";
    position: absolute;
    top: 16px;
    left: 6px;
    width: 3px;
    height: 100%;
    background-color: #28a745;
    z-index: -1;
    }

    .service-list-item:last-child::after {
      display: none; /* Hide the line after the last item */
    }
  </style>
</head>
<body>
  <div class="container">
    <ul class="service-list">
      <li class="service-list-item"><h3>Service One</h3><p class="m-0">Hide the line after the last item</p><p class="m-0">Hide the line after the last item</p></li>
      <li class="service-list-item"><h3>Service One</h3><p class="m-0">Hide the line after the last item</p><p class="m-0">Hide the line after the last item</p></li>
      <li class="service-list-item"><h3>Service One</h3><p class="m-0">Hide the line after the last item</p><p class="m-0">Hide the line after the last item</p></li>
      <li class="service-list-item"><h3>Service One</h3><p class="m-0">Hide the line after the last item</p><p class="m-0">Hide the line after the last item</p></li>
    </ul>
  </div>
</body>
</html>
