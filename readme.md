<!-- Landing/Home Page -->
<!doctype html>
<html lang="en">
<head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">
    <link rel="stylesheet" type="text/css" href="style.css">
    <title>Bootstrap Visualization Dashboard</title>
</head>
<body>
    <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js" integrity="sha384-UO2eT0CpHqdSJQ6hJty5KVphtPhzWj9WO1clHTMGa3JDZwrnQq4sF86dIHNDz0W1" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js" integrity="sha384-JjSmVgyd0p3pXB1rRibZUAYoIIy6OrQ6VrjIEaFf/nJGzIxFDsf4x0xIM+B07jRM" crossorigin="anonymous"></script>
    <div class="navigation">
        <nav class="navbar navbar-expand-lg navbar-light bg-light">
            <a class="navbar-brand" style="background-color: black;" href="index.html">Latitude</a>
            <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNavDropdown" aria-controls="navbarNavDropdown" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNavDropdown">
                <ul class="navbar-nav ml-auto">
                    <li class="nav-item dropdown">
                        <a class="nav-link dropdown-toggle" href="#" id="navbarDropdownMenuLink" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                            Plots
                        </a>
                        <div class="dropdown-menu" aria-labelledby="navbarDropdownMenuLink">
                            <a class="dropdown-item" href="temp.html">Max Temperature</a>
                            <a class="dropdown-item" href="humidity.html">Humidity</a>
                            <a class="dropdown-item" href="cloudiness.html">Cloudiness</a>
                            <a class="dropdown-item" href="wind_speed.html">Wind Speed</a>
                        </div>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="comparison.html">Comparison</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="data.html">Data</a>
                    </li>
                </ul>
            </div>
        </nav>
    </div>
    <!-- Content -->
    <div class="container">
        <div class="row">
            <div class="col-lg-7 col-md-12">
                <div class="box" style="padding-bottom: 20px;">
                    <h3 class="title">Summary: Latitude vs. X</h3>
                    <hr>
                    <img src="City_Latitude_vs_Max_Temperature.png" class="vizualization rounded float-left" alt="Max Temperature Graph">
                    <p>The purpose of this project was to analyze how weather changes as you get closer to the equator. 
                    To accomplish this analysis, wefirst pulled data from the OpenWeatherMap API to assemble a dataset on over 500 cities.</p>
                    <p>After assembling the dataset, we used Matplotlib to plot various aspects of the weather vs. latitude. 
                    Factors we looked at included: temperature, cloudiness, wind speed, and humidity. This site provides the source data and
                    visualizations created as part of the analysis, as well as explanations and descriptions of any trends and correlations witnessed.</p>
                </div>
            </div>
            <div class="col-lg-5 col-md-12">
                <!-- Right Content Box -->
                <div class="box">
                    <h3 class="title">Visualizations</h3>
                    <hr>
                    <div class="container">
                        <div class="row" style="padding-bottom: 30px;">
                            <div class="col-6">
                                <a href="temp.html">
                                <img class="panel" src="City_Latitude_vs_Max_Temperature.png" alt="Max Temperature Graph">
                                </a>
                            </div>
                            <div class="col-6">
                                <a href="humidity.html">
                                <img class="panel" src="City_Latitude_vs_Humidity.png" alt="Humidity Graph">
                                </a>
                            </div>
                        </div>
                        <div class="row" style="padding-bottom: 30px;">
                            <div class="col-6">
                                <a href="cloudiness.html">
                                <img class="panel" src="City_Latitude_vs_Cloudiness.png" alt="Cloudiness Graph">
                                </a>
                            </div>
                            <div class="col-6">
                                <a href="wind_speed.html">
                                    <img class="panel" src="City_Latitude_vs_Wind_Speed.png" alt="Wind Speed Graph">
                                </a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <!-- Footer -->
    <footer>
        <div class="footer">&copy; Copyright Jenny Yi 2020. All Rights Reserved.</div>
    </footer>
</body>
</html>
©
