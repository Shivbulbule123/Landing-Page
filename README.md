# Landing-Page
Creating landing page by using HTML, CSS
  <!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF - 8" />
    <meta http-equiv="X-UA-compitable" content="IE=edge" />
    <meta name=" viewpoint" content="width=device-width, initial-scale=1.0" />
    <title>Rajesh daily Groceery</title>
    <link rel="stylesheet" href="style.css" />
    <link rel="stylesheet" href="utils.css" />
  </head>

  <body>
    <div class="container mx-auto">
      <header>
        <nav class="flex justify-between">
          <div class="logo font-bold flex items-center text-blue">
            Rajesh Grocery Store
          </div>
          <ul class="navbar flex items-center">
            <li>Home</li>
            <li>About</li>
            <li>Services</li>
            <li>Contact Us</li>
            <li><button class="btn">Join Now</button></li>
          </ul>
        </nav>
      </header>

      <img class="grocery-image" src="./Grocery.jpeg" alt="" />

      <div>
        <h1 class="my-1 text-center">Everyday Discount Day</h1>
        <p class="text-center">
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Eum aliquam
          nemo placeat officia eveniet consequuntur incidunt amet! Adipisci
          nobis incidunt, fugiat velit esse dolore. Odit atque fugiat dolor quod
          nesciunt
        </p>
      </div>
      <div class="topright flex justify-center">
        <img src="./food-cart.jpg" alt="" width="500" height="300" />
      </div>

      <main class="min-h-screen">
        <hr />
        <section class="section2">
          <h1 class="text-center my-2">Material</h1>
          <p class="text-center">
            Lorem ipsum dolor sit, amet consectetur adipisicing elit. Ducimus
            adipisci maiores sed obcaecati saepe totam repudiandae quia
            perspiciatis corrupti molestias, optio itaque quaerat aperiam
            accusantium a eaque iusto id tempore!
          </p>

          <div class="Boxes flex">
            <div class="Box">
              <h1>Offer</h1>
              <ul>
                <li>20%</li>
                <li>Buy-2 get-1-free</li>
                <li>Email support</li>
                <li>Help center access</li>
                <li><button class="btn">Signup Now</button></li>
              </ul>
            </div>
            <div class="Box">
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Assumenda
              dicta, et commodi accusamus voluptatum nihil eius, quibusdam
              exercitationem repellendus, aut nam necessitatibus! Provident
              ipsum sunt tenetur perspiciatis nobis aut facilis!

              <h2>Pro</h2>
              <ul>
                <li class="Highlighted">Limited offer</li>
                <li>Email support</li>
                <li>Help center access</li>
                <li><button class="btn">Signup Now</button></li>
              </ul>
            </div>

            <div class="Box">
              <h3>Enterprises</h3>
              <ul>
                <li class="Highlighted">Save 1000 off</li>
                <li>free wifi</li>
                <li>Email support</li>
                <li>Help center access</li>
                <li><button class="btn">Signup Now</button></li>
              </ul>

              <div class="Box">
                Lorem ipsum dolor sit amet consectetur adipisicing elit.
                Architecto corrupti ab tempora, impedit, autem molestiae error
                dolore inventore voluptate eum, exercitationem placeat. Esse
                totam quo aliquam vel cum voluptatem dolor?
              </div>
            </br>
            </div>
          </div>
        </section>
        <hr />
        <section>
          <div class="Container Plantable">
            <table class="table text-center">
              <thead>
                <tr>
                  <th></th>
                  <th>Offer</th>
                  <th>Pro</th>
                  <th>Enterprises</th>
                </tr>
              </thead>
              <tbody>
                <tr>
                  <th scope="row" class="text-start">Public</th>
                  <td>
                    <svg class="bi" width="24" height="24">
                      <use xlink:href="#check" />
                    </svg>
                  </td>
                  <td>
                    <svg class="bi" width="24" height="24">
                      <use xlink:href="#check" />
                    </svg>
                  </td>
                  <td>
                    <svg class="bi" width="24" height="24">
                      <use xlink:href="#check" />
                    </svg>
                  </td>
                </tr>

                <tr>
                  <th scope="row" class="text-start">Private</th>
                  <td></td>
                  <td>
                    <svg class="bi" width="24" height="24">
                      <use xlink:href="#check" />
                    </svg>
                  </td>
                  <td>
                    <svg class="bi" width="24" height="24">
                      <use xlink:hre="#check" />
                    </svg>
                  </td>
                </tr>

                <tr>
                  <th scope="row" class="text-start">Permission</th>
                  <td>
                    <svg class="bi" width="24" height="24">
                      <use xlink:href="#check" />
                    </svg>
                  </td>
                  <td>
                    <svg class="bi" width="24" height="24">
                      <use xlink:href="#check" />
                    </svg>
                  </td>
                  <td>
                    <svg class="bi" width="24" height="24">
                      <use xlink:href="#check" />
                    </svg>
                  </td>
                </tr> 
                
              </tbody>
            </table>
          </div>
        </section>
      </main>
      <footer>Copyright &copy; rajeshgrocery.com | All rights reserved</footer>
    </div>
  </body>
</html>
