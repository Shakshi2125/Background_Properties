<!DOCTYPE html>
<html lang="en"><head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
      * {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
      }
      .nav {
        max-width: 100vw;
        background: linear-gradient();
        padding: 2%;
        background: linear-gradient(
          rgba(0, 0, 0, 1),
          rgba(0, 0, 0, 0.9),
          rgba(0, 0, 0, 0.8),
          rgba(0, 0, 0, 0.7)
        );
      }
      .nav_sub {
        display: inline-block;
        margin-inline: 5%;
        color: white;
      }
      .active {
        background-color: white;
        color: black;
        padding: 0.6% 1.5%;
      }
      .main-1 {
        background-image: url("https://e0.pxfuel.com/wallpapers/850/763/desktop-wallpaper-construction-site-construction-work.jpg");
        height: 500px;
        width: 100%;
        background-repeat: no-repeat;
        background-size: cover;
      }
      .main-2 {
        height: 500px;
        width: 100%;
      }
      .main-2 > img {
        margin: 2%;
        width: 29%;
        height: 90%;
      }
      .main-3 {
        padding: 2%;
        background-color: black;
        background-repeat: no-repeat;
        background-size: cover;
        height: 500px;
      }
      .main-3-sub1 {
        width: 45%;
        display: inline-block;
        color: white;
      }
      .main-3-sub2 {
        width: 45%;
        display: inline-block;
        margin: 1%;
      }
    </style>
  </head>
  <body>
    <div class="nav">
      <div class="nav_sub active">Home</div>
      <div class="nav_sub">Services</div>
      <div class="nav_sub">About</div>
      <div class="nav_sub">Project</div>
      <div class="nav_sub">Cotact</div>
    </div>
    <div class="main-1"></div>
    <div class="main-2">
      <img src="https://static7.depositphotos.com/1010826/675/v/450/depositphotos_6751521-stock-illustration-tower-cranes.jpg" alt="img-1">
      <img src="https://wallpapers.com/images/featured/civil-engineering-pa6hvqgpaqfw6mgb.jpg" alt="img-2">
      <img src="https://c1.wallpaperflare.com/preview/734/797/226/construction-site-building-concrete.jpg" alt="img-3">
    </div>
    <div class="main-3">
      <p class="main-3-sub1">
        Lorem, ipsum dolor sit amet consectetur adipisicing elit. Quo placeat
        consectetur quasi, molestiae omnis fugiat pariatur totam dolorum dolore!
        Vero consequatur quaerat magnam possimus ut quam veritatis, quisquam hic
        minima consequuntur doloremque, debitis dolorem mollitia totam alias
        eius provident illum? Nostrum exercitationem quidem iure? Architecto
        nulla nesciunt ad nobis aliquam?Lorem ipsum dolor sit amet consectetur
        adipisicing elit. Quidem veritatis dolorem iste minima rerum similique
        atque laborum blanditiis, dolore ratione molestiae doloribus labore,
        nobis sunt earum iure, dolores rem animi quas sequi error consequuntur?
        Sint minus repellendus facere nemo nobis vitae itaque commodi et quaerat
        magni maxime quam deserunt quod quis illo atque accusamus explicabo id
        suscipit, sed a, error, inventore ut maiores? Necessitatibus obcaecati
        cum delectus quos incidunt, adipisci molestias laboriosam, cumque amet
        itaque rem fugit dolores totam id nemo non quae mollitia blanditiis
        cupiditate assumenda. Ex vitae libero deleniti, dignissimos ratione
        voluptates consequuntur quae expedita. In, temporibus facilis?
      </p>
      <img src="https://media.istockphoto.com/id/1202296779/photo/black-and-white-photo-structure-of-steel-for-building-construction.jpg?s=1024x1024&amp;w=is&amp;k=20&amp;c=zB6oytRiAmzlr-gQ1Qj0GTC7YOjo6fd5jeiW8Iuz78M=" class="main-3-sub2">
    </div>
</body>
</html>