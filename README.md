# bootstrap-card-columns
Often, you will need to spread an unordered (or ordered) list across multiple columns. Rather than arbitrary breaking the lists and creating separate columns, you can use card columns so that the content dynamically fits to whatever card column dimensions you specify.

## Tutorial
For detailed instruction's, view Solodev's [Using Bootstrap Card Columns to Dynamically Configure Your Unordered Lists Across Multiple Columns](https://www.solodev.com/blog/web-design/using-bootstrap-card-columns-to-dynamically-configure-your-unordered-lists-across-multiple-columns.stml)

## Demo
Try out a working example on [JSFiddle](https://jsfiddle.net/solodev/2tqpog3r/).

## HTML
The tutorial contains the following basic HTML markup.

```
<header class="header position-relative">
  <div class="container">
    <div class="row">
      <div class="col-lg-3 col-md-4 col-6 header--logo">
        <a href="/"><img src="https://raw.githubusercontent.com/solodev/bootstrap-card-columns/master/images/logo.png" class="img-fluid" alt="LunarXP Logo"></a>
      </div>
      <div class="header--menubar col-lg-9 offset-lg-0 col-md-2 offset-md-6 col-6 position-static">
        <div class="header--menu d-lg-flex d-none justify-content-right">
          <ul>
            <li><a href="#">Locations</a></li>
            <li><a href="#">Products</a></li>
            <li><a href="#">Shop</a></li>
            <li><a href="#">Contact</a></li>
            <li class="menu-item-has-children btn">
              <a>I Want To</a>
              <div class="mega-menu dropdown i-want-to">
                <div class="container">
                  <div class="menu-bg">
                    <div class="row">
                      <ul class="sub-menu card-columns">

                        <li>
                          <a href="#" class="title"><span>Apply For</span></a>
                          <ul>
                            <li><a href="#">Business Tax</a></li>
                            <li><a href="#">Contractor License</a></li>
                            <li><a href="#">Pilot License</a></li>
                            <li><a href="#">Job</a></li>
                          </ul>
                        </li>

                        <li>
                          <a href="#" class="title"><span>Buy</span></a>
                          <ul>
                            <li><a href="#">Parking Pass</a></li>
                            <li><a href="#">Pet License</a></li>
                          </ul>
                        </li>

                        <li>
                          <a href="#" class="title">
                            <span>Dispose Of</span></a>
                          <ul>
                            <li><a href="#">Electronics</a></li>
                            <li><a href="#">Garbage</a></li>
                            <li><a href="#">Hazardous Waste</a></li>
                          </ul>

                        </li>
                        <li>
                          <a href="#" class="title"><span>Find</span></a>
                          <ul>
                            <li><a href="#">Medical Services Facilities</a></li>
                            <li><a href="#">Supply Centers</a></li>
                            <li><a href="#">Site-to-Site Transportation</a></li>
                            <li><a href="#">Operational Locations</a></li>
                            <li><a href="#">Community Activity Centers</a></li>
                            <li><a href="#">Laboratories</a></li>
                            <li><a href="#">Space Transportation</a></li>
                            <li><a href="#">Project Status Updates</a></li>
                            <li><a href="#">Schools</a></li>
                            <li><a href="#">Social Media</a></li>
                          </ul>

                        </li>
                        <li>
                          <a href="#" class="title"><span>Pay</span></a>
                          <ul>
                            <li><a href="#">Parking Ticket</a></li>
                            <li><a href="#">Taxes</a></li>
                            <li><a href="#">Utility Bill</a></li>
                          </ul>
                        </li>

                        <li>
                          <a href="#" class="title"><span>Register</span></a>
                          <ul>
                            <li><a href="#">LunarXP App</a></li>
                            <li><a href="#">Recreation</a></li>
                            <li><a href="#">Special Needs</a></li>
                            <li><a href="#">Vehicle</a></li>
                          </ul>

                        </li>

                        <li>
                          <a href="#" class="title"><span>Report</span></a>
                          <ul>
                            <li><a href="#">Animal Cruelty</a></li>
                            <li><a href="#">Code Violatoin</a></li>
                            <li><a href="#">Illegal Dumping</a></li>
                          </ul>

                        </li>
                        <li>
                          <a href="#" class="title">
                            <span>Reserve</span></a>
                          <ul>
                            <li><a href="#">Colony Facility</a></li>
                            <li><a href="#">Transit Ride</a></li>
                          </ul>
                        </li>

                        <li>
                          <a href="#" class="title"><span>Sign Up For</span></a>
                          <ul>
                            <li><a href="#">Pilot Training</a></li>
                            <li><a href="#">Volunteer</a></li>
                          </ul>

                        </li>
                        <li>
                          <a href="#" class="title"><span>Submit</span></a>
                          <ul>
                            <li><a href="#">Job Application</a></li>
                            <li><a href="#">Public Records Request</a></li>
                            <li><a href="#">Question</a></li>
                          </ul>
                        </li>

                        <li>
                          <a href="#" class="title"><span>Watch</span></a>
                          <ul>
                            <li><a href="#">SpaceJet TV</a></li>
                            <li><a href="#">LunarXP Live</a></li>
                            <li><a href="#">LunarXP Videos</a></li>
                            <li><a href="#">Space Shuttle Launches</a></li>
                          </ul>
                        </li>


                        <li class="mt-4">
                          <a href="#"><span>View All Items</span></a>
                        </li>
                      </ul>
                    </div>
                  </div>
                </div>
              </div>
            </li>
          </ul>
        </div><!-- .menu-->
        <button id="sidenav-open-btn" class="menu-hamburger d-md-inline-block d-lg-none menu-hamburger position-absolute pointer p-0">
          <span class="icon-bar"></span>
          <span class="icon-bar"></span>
          <span class="icon-bar"></span>
        </button>
      </div>
    </div>
  </div>
</header>
```

## CSS
All required CSS is contained with style.css

## External Resources
This tutorial includes the following third party resources.

```
<!-- Bootstrap CSS -->
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/css/bootstrap.min.css" integrity="sha384-Vkoo8x4CGsO3+Hhxv8T/Q5PaXtkKtu6ug5TOeNV6gBiFeWPGFN9MuhOf23Q9Ifjh" crossorigin="anonymous">
<!-- FontAwesome CSS -->
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.css">
<!-- jQuery first, then Popper.js, then Bootstrap JS -->
<script src="https://code.jquery.com/jquery-3.4.1.slim.min.js" integrity="sha384-J6qa4849blE2+poT4WnyKhv5vZF5SrPo0iEjwBvKU7imGFAV0wwj1yYfoRSJoZ+n" crossorigin="anonymous"></script>
<script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js" integrity="sha384-Q6E9RHvbIyZFJoft+2mJbHaEWldlvI9IOYy5n3zV9zzTtmI3UksdQRVvoxMfooAo" crossorigin="anonymous"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/js/bootstrap.min.js" integrity="sha384-wfSDF2E50Y2D1uUdj0O3uMBJnjuUD4Ih7YwaYd1iqfktj0Uod8GCExl3Og8ifwB6" crossorigin="anonymous"></script>
```