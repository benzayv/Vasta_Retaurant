<head>
  <title>Mini Filipino Restaurant Menu</title>
  <style>
    body {
      background: url('https://assets.simpleviewinc.com/simpleview/image/upload/c_fill,h_608,q_75,w_1080/v1/clients/houston/14657305_10153797372005583_461865778160703606_n_dda2b5a5-e545-4d51-b403-5f6206b1bd8b.jpg') ;
      background-size: cover;
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
    }

    header {
      background-color: #8C1D40;
      color: #FFF;
      padding: 25px;
      font-size: 17pt;             
      text-align: center;
    }

    h1 {
      margin: 0;
    }

    nav {
      background-color: #C70039;
      color: #FFF;
      display: flex;
      justify-content: space-between;
      padding: 15px;
    }

    nav a {
      color: #FFF;
      padding: 15px;
      text-decoration: none;
    }

    nav a:hover {
      background-color: #FFF;
      color: #C70039;
    }

    section {
      display: flex;
      flex-wrap: wrap;
      justify-content: space-around;
      padding: 20px;
    }

    .table_b {
      background-color: #FFF;
      border-radius: 10px;
      box-shadow: 3px 3px 5px #999;
      margin: 20px;
      padding: 20px;
      position: absolute;
      top: 50%;
      left: 50%;
      transform: translate(-59%, 150%);
      width: 500px
      
    }

     table.table_b h2 {
      border-bottom: 1px solid #BBB;
      font-size: 1.5em;
      margin-bottom: 10px;
      padding-bottom: 5px;
       position: absolute;
      top: 50%;
      left: 50%;
      transform: translate(-60%, 130%);
    }

     table.table_b p {
      font-size: 1.1em;
      margin: 0;
    }

    table {
      background-color: #FFF;
      border-radius: 10px;
      box-shadow: 3px 3px 5px #666;
      margin: 20px;
      padding: 20px;
      width: 300px;
    }

    table h2 {
      border-bottom: 1px solid #EEE;
      font-size: 1.5em;
      margin-bottom: 10px;
      padding-bottom: 5px;
    }

    table p {
      font-size: 1.1em;
      margin: 0;
    }

    img {
      border-radius: 10px;
      height: 200px;
      object-fit: cover;
      width: 100%;
    }

    footer {
      background-color: #8C1D40;
      color: #FFF;
      padding: 1px;
      text-align: center;
      position: fixed;
      bottom: 0;
      width: 100%;
    }

    .ctc {
      background-color: #C70039;
      color: #FFF;
      display: flex;
      justify-content: space-between;
      padding: 20px;
    }

    .ctc a {
      color: #FFF;
      font-size: 37pt;             
      padding: 20px;
      text-decoration: none;
    }

    .ctc a:hover {
      background-color: #FFF;
      color: #C70039;
    }

    .cart {
      display: none;
      position: fixed;
      top: 0;
      right: 0;
      left: 0;
      background-color: #ffffff;
      padding: 30px;
      border-left: 1px solid #EEE;
      width: 300px;
      cursor: move;
    }

    /* Additional styles for separate pages */
    .content {
      color: #000000;
      padding: 20px;
    }

    .contact-info {
      display: flex;
      flex-wrap: wrap;
      justify-content: space-around;
      padding: 10px;
    }

  </style>
</head>

<body>
  <header>
    <h1>VASTA RESTAURANT</h1>
    <p style="font-size: 17pt;">Mini Filipino Restaurant</p>
   	
 
  </header>

  <nav>
    <a href="#home" onclick="showPage('home')"style="font-size: 17pt;">Home</a>
    <a href="#menu" onclick="showPage('menu')"style="font-size: 17pt;">Menu</a>
    <a href="#about" onclick="showPage('about')"style="font-size: 17pt;">About</a>
    <a href="#contact" onclick="showPage('contact')"style="font-size: 17pt;">Contact</a>
    <a href="#cart" onclick="showPage('cart')"style="font-size:17pt;">Cart</a>
  </nav>

  <div class="content" id="home">
    <h2 style="font-size: 47pt;">Welcome to our cozy Mini Restaurant!</h2>
        <p style="font-size: 25pt;">We are thrilled to have you join us for a delightful dining experience. Take a seat, unwind, and allow us to treat you to a memorable experience. Our team is dedicated to providing you with exceptional service and mouthwatering dishes. We aim to make your visit truly special. Thank you for choosing us, and we hope you enjoy your time with us!</p>
  </div>

  <div class="content" id="menu" style="display: none;">

	<section>
		<table>
		 <tr>
		 <td>
		 <h2>Chicken Dishes</h2>
		 <img src="https://www.eatwithcarmen.com/wp-content/uploads/2022/09/chicken-adobo_.jpg" alt="Adobo">
		 <h1>Adobo</h1>
		 <h3>About Adobo:</h3>
		 <h5> Adobo is a dish that is usually made with meat (chicken, pork, or beef) marinated in vinegar, soy sauce, garlic, and other spices. The meat is slowly cooked until it becomes tender and flavorful. Adobo is often served with rice and is a staple dish in many Filipino households.</h5>		 
		 <button onclick="addToCart('Adobo', 150)"style="font-size: 15pt;">Php 150 Add to Cart</button>
		 </td>
		 </tr>
  	</table>
		
		
		<table>
		  <tr>
			<td>   
			<h2>Chicken Dishes</h2>
			<img src="https://www.allrecipes.com/thmb/WSSoRAz2IygrMPkiJxHPbt9gqMg=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc()/8635-southern-fried-chicken-ddmfs_4x3-90736ab31a7a4bb59eb04e2380ccebe7.jpg" alt="Fried Chicken">
			<h1>Fried Chicken</h1>
			<h3>About Fried Chicken:</h3>
			<h5>Fried chicken is a dish consisting of chicken pieces that have been coated with seasoned flour or batter and pan-fried, deep fried, pressure fried, or air fried. The breading adds a crisp coating or crust to the exterior of the chicken while retaining juices in the meat.</h5>
		 <button onclick="addToCart('Fried Chicken', 120)"style="font-size: 15pt;">Php 120 Add to Cart</button>
			</td>
			</tr>
		</table>
	
		
		<table>
		  <tr>
			<td>   
			<h2>Chicken Dishes</h2>
			<img src="https://travellingfoodie.net/wp-content/uploads/2022/03/Exotic-Filipino-Food-Bizarre-Food-Philippines-Travelling-Foodie-8-1024x683.jpg.webp" alt="Isaw">    
			<h1>Isaw</h1>
			<h3>About Isaw:</h3>
      <h5>Isaw is a street food made from barbecued pig or chicken intestines. It is a type of inihaw. The intestines are cleaned several times and are then either boiled, then grilled on sticks. For presentability, the intestines are usually applied with orange food coloring.</h5>
		 <button onclick="addToCart('Isaw', 180)"style="font-size: 15pt;">Php 180 Add to Cart</button>
			</td>
			</tr>
		</table>
		
		
		<table>
		  <tr>
			<td>   
			<h2>Chicken Dishes</h2>
			<img src="https://assets.unileversolutions.com/recipes-v2/110276.jpg" alt="Tinola">
			<h1>Tinola</h1>
			<h3>About Tinola:</h3>
			<h5>Tinolang manok is a Filipino chicken soup. It can consist of various chicken cuts and internal organs cooked in a flavorful broth alongside green papaya and chili pepper or malunggay leaves. The broth is usually generously seasoned with ginger, garlic, and fish sauce, and the soup is often served over plain white rice.</h5>
		 <button onclick="addToCart('Tinola', 160)"style="font-size: 15pt;">Php 160 Add to Cart</button>
			</td>
			</tr>
		</table>
		
		
		<table>
		  <tr>
			<td>   
			<h2>Pork Dishes</h2>
			<img src="https://panlasangpinoy.com/wp-content/uploads/2021/08/Killer-Pork-Sinigang-jpg.webp?fbclid=IwAR0Q1gApG_7o1GLTr6S0AkKGmuw4xuNM-gx7D7vQthsX5MPw11Sx9mXNAy0" alt="Sinigang">
			<h1>Sinigang</h1>
			<h3>About Sinigang:</h3>
			<h5>Sinigang is a Filipino soup or stew characterized by its sour and savory taste. It is most often associated with tamarind (Filipino: sampalok), although it can use other sour fruits and leaves as the souring agent. It is one of the more popular dishes in Filipino cuisine. The soup is usually accompanied by rice.</h5>
		 <button onclick="addToCart('Sinigang', 140)"style="font-size: 15pt;">Php 140 Add to Cart</button>
			</td>
			</tr>
		</table>
		
		
		<table>
		  <tr>
			<td>   
			<h2>Pork Dishes</h2>
			<img src="https://assets.unileversolutions.com/v1/85775930.jpg" alt="Kare-kare">
			<h1>Kare-kare</h1>
			<h3>About Kare-Kare:</h3>
			<h5>Kare-kare is a stew (kare derives from "curry") that features a thick savory peanut sauce. It is generally made from a base of stewed oxtail, beef tripe, pork hocks, calves' feet, pig's feet or trotters, various cuts of pork, beef stew meat, and occasionally offal.</h5>
		 <button onclick="addToCart('Kare-kare', 200)"style="font-size: 15pt;">Php 200 Add to Cart</button>
			</td>
			</tr>
		</table>
		
		
		<table>
		  <tr>
			<td>   
			<h2>Pork Dishes</h2>
			<img src="https://i0.wp.com/www.angsarap.net/wp-content/uploads/2017/02/Pinakbet-Wide.jpg?fit=1080%2C720&ssl=1" alt="Pinakbet">
			<h1>Pinakbet</h1>
      <h3>About Pinakbet:</h3>
      <h5>Pinakbet (also called pakbet) is an indigenous Filipino dish from the northern regions of the Philippines. Pinakbet is made with a variety of mixed vegetables flavored with bagoóng. The word is the contracted from the Ilokano word pinakebbet, meaning "shrunk" or "shriveled."</h5>
		 <button onclick="addToCart('Pinakbet', 180)"style="font-size: 15pt;">Php 180 Add to Cart</button>
			</td>
			</tr>
		</table>
		
		
		<table>
		  <tr>
			<td>   
			<h2>Pork Dishes</h2>
			<img src="https://th.bing.com/th/id/OIP.YqNdU65X0vEdL4G7Wk6NaQHaFj?w=230&h=180&c=7&r=0&o=5&dpr=1.3&pid=1.7.jpg" alt="Lechon kawali">
			<h1>Lechon kawali</h1>
      <h3>About Lechon Kawali:</h3>
      <h5>Lechon kawali, also known as lechon de carajay or litsong kawali in Tagalog, is a Filipino recipe consisting of pork belly slabs deep-fried in a pan or wok (kawali). It is seasoned beforehand, cooked then served in cubes.</h5>
		 <button onclick="addToCart('Lechon kawali', 250)"style="font-size: 15pt;">Php 250 Add to Cart</button>
			</td>
			</tr>
		</table>
		
		
		<table>
		  <tr>
			<td>   
			<h2>Beef Dishes</h2>
			<img src="https://www.thespruceeats.com/thmb/BJnw-h62SdxnpnI4ynYSrHVSpxI=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc()/garlicky-filipino-bistek-3030379-hero-01-f916301cac884a309b4ead5ed8bee443.jpg" alt="Bistek">
			<h1>Bistek</h1>
			<h3>About Bistek:</h3>
			<h5>Bistek also known as bistek tagalog or karne frita, is a Filipino dish consisting of thinly-sliced beefsteak braised in soy sauce, calamansi juice, garlic, ground black pepper, and onions cut into rings.</h5>
		 <button onclick="addToCart('Bistek', 190)"style="font-size: 15pt;">Php 190 Add to Cart</button>
			</td>
			</tr>
		</table>
		
		
		<table>
		  <tr>
			<td>   
			<h2>Beef Dishes</h2>
			<img src="https://pilipinasrecipes.com/wp-content/uploads/2017/05/Pork-Afridata-Recipe.jpg" alt="Balbacua">
			<h1>Balbacua</h1>
			<h3>About Balbacua:</h3>
			<h5>Balbacua is a Filipino beef stew made from beef, collagen-rich beef parts (oxtail, skin, and joints), and various spices cooked for several hours until very tender.</h5>
		 <button onclick="addToCart('Balbacua', 210)"style="font-size: 15pt;">Php 210 Add to Cart</button>
			</td>
			</tr>
		</table>
		
		
		<table>
		  <tr>
			<td>   
			<h2>Beef Dishes</h2>
			<img src="https://panlasangpinoy.com/wp-content/uploads/2019/03/Beef-Kaldereta.jpg" alt="Kaldireta">
			<h1>Kaldireta</h1>
			<h3>About Kaldireta:</h3>
			<h5>Kaldereta or caldereta is a goat meat stew from the Philippines. Variations of the dish use (beef, chicken, or pork.)Commonly, the goat meat is stewed with vegetables and liver paste. Vegetables may include tomatoes, potatoes, olives, bell peppers, and hot peppers.</h5>
		 <button onclick="addToCart('Kaldireta', 200)"style="font-size: 15pt;">Php 200 Add to Cart</button>
			</td>
			</tr>
		</table>
		
		
		<table>
		  <tr>
			<td>   
			<h2>Beef Dishes</h2>
			<img src="https://www.pinoyrecipe.net/wp-content/uploads/2021/03/Chicken-Afritada.jpg" alt="Afritada">
			<h1>Afritada</h1>
			<h3>About Afritada:</h3>
			<h5>Afritada is a Philippine dish consisting of chicken, beef, or pork braised in tomato sauce with carrots, potatoes, and red and green bell peppers.</h5>
		 <button onclick="addToCart('afritada', 180)"style="font-size: 15pt;">Php 180 Add to Cart</button>
			</td>
			</tr>
		</table>


		<table>
		  <tr>
			<td>   
			<h2>Cold Drinks</h2>
			<img src=" https://www.encopadebalon.com/3493-large_default/coca-cola-pack-24-cans-33-cl.jpg"" alt="Cola">
			<h1>Cola </h1>
		 <button onclick="addToCart('Pares', 35)"style="font-size: 15pt;">Php 35 Add to Cart</button>
			</td>
			</tr>
		</table>


<table>
		  <tr>
			<td>   
			<h2>Cold Drinks</h2>
			<img src="https://media.pickaroo.com/media/thumb/variant_photos/2022/5/17/PaHzqjhAMKm6WcCwjDZ6Hi_watermark_400.jpg" alt="7 Up">
			<h1>7 Up</h1>
		 <button onclick="addToCart('7 Up',35 )"style="font-size: 15pt;">Php 35 Add to Cart</button>
			</td>
			</tr>
		</table>


		<table>
		  <tr>
			<td>   
			<h2>Cold Drinks</h2>
			<img src="https://ucccafe.mugengroup.ph/wp-content/uploads/sites/4/2023/09/SPRITE-min.jpg" alt="Sprite">
			<h1>Sprite</h1>
		 <button onclick="addToCart('Sprite',35 )"style="font-size: 15pt;">Php 35 Add to Cart</button>
			</td>
			</tr>
		</table>


		<table>
		  <tr>
			<td>   
			<h2>Cold Drinks</h2>
			<img src="https://amici.ph/cdn/shop/products/mug-rootbeer-can_1200x.jpg?v=1518899304" alt="Root Beer">
			<h1>Root Beer</h1>
		 <button onclick="addToCart('Root Beer',35 )"style="font-size: 15pt;">Php 35 Add to Cart</button>
			</td>
			</tr>
		</table>

	
		<table>
		  <tr>
			<td>   
			<h2>Cold Drinks</h2>
			<img src="https://frostingandfettuccine.com/wp-content/uploads/2022/12/Caramel-Iced-Coffee-6.jpg" alt="Ice Coffee">
			<h1>Ice Coffee</h1>
		 <button onclick="addToCart('Ice Coffee',70 )"style="font-size: 15pt;">Php 70 Add to Cart</button>
			</td>
			</tr>
		</table>

	
		<table>
		  <tr>
			<td>   
			<h2>Cold Drinks</h2>
			<img src="https://www.alphafoodie.com/wp-content/uploads/2020/11/Orange-Juice-1-of-1.jpeg" alt="Juice">
			<h1>Juice</h1>
		 <button onclick="addToCart('Juice',35 )"style="font-size: 15pt;">Php 35 Add to Cart</button>
			</td>
			</tr>
		</table>

		
		<table>
		  <tr>
			<td>   
			<h2>Hot Drinks</h2>
			<img src="https://thehealthytart.com/wp-content/uploads/2017/03/Ginger-and-Lemon-tea.jpg" alt="Malunggay Tea">
			<h1>Malunggay Tea</h1>
		 <button onclick="addToCart('Malunggay Tea',35 )"style="font-size: 15pt;">Php 35 Add to Cart</button>
			</td>
			</tr>
		</table>


		<table>
		  <tr>
			<td>   
			<h2>Hot Drinks</h2>
			<img src="https://thehealthytart.com/wp-content/uploads/2017/03/Ginger-and-Lemon-tea.jpg" alt="Ginger Tea">
			<h1>Ginger Tea</h1>
		 <button onclick="addToCart('Ginger Tea',35 )"style="font-size: 15pt;">Php 35 Add to Cart</button>
			</td>
			</tr>
		</table>


		<table>
		  <tr>
			<td>   
			<h2>Hot Drinks</h2>
			<img src="https://img.jakpost.net/c/2023/09/12/2023_09_12_142304_1694508173._large.jpg" alt="Blue Ternatea Tea">
			<h1>Blue Ternatea Tea</h1>
		 <button onclick="addToCart('Blue Ternatea Tea',35 )"style="font-size: 15pt;">Php 35 Add to Cart</button>
			</td>
			</tr>
		</table>


		<table>
		  <tr>
			<td>   
			<h2>Hot Drinks</h2>
			<img src="https://i.pinimg.com/564x/f5/6d/19/f56d19b0a266c645ffceb6c6588b5a85.jpg" alt="Kalamansi Tea">
			<h1>Kalamansi Tea</h1>
		 <button onclick="addToCart('Kalamansi Tea',35 )"style="font-size: 15pt;">Php 35 Add to Cart</button>
			</td>
			</tr>
		</table>
	</section>

  </div>


  <div class="content" id="cart" style="display: none;">
    <h2 style="font-size: 47pt;">Your Cart</h2>
    <div id="cart-items">
            </div>
    <div id="cart-total">
      <h3>Total: <span id="total-amount">Php 0</span></h3>
    </div>
    <button onclick="checkout()" style="font-size: 17pt;">Checkout</button>
  </div>

    <div class="content" id="about" style="display: none;">
        <h2 style="font-size: 47pt;">Hello our Dear Costumers!</h2>
        <p style="font-size: 25pt;">Here at VASTA,we are passionate about serving delicious, high-quality meals in a welcoming and comfortable atmosphere. Our menu is carefully crafted to offer a variety of dishes that cater to different tastes and dietary preferences.</p>
        <p style="font-size: 25pt;">We invite you to join us at BASTA and experience the warmth and hospitality that our mini restaurant has to offer. Whether you're looking for a quick bite or a leisurely meal, we look forward to serving you.</p>
    </div>

    <div class="content" id="contact" style="display: none;">
        <div class="contact-info">


     <div>
    <table>
      <tr>
      <td>
      <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/f/fb/Facebook_icon_2013.svg/800px-Facebook_icon_2013.svg.png" alt="Vasta Restaurant">
      <h1>Vasta Restaurant</h1>
      <p>Phone Number: <a href="tel:09947522520">0994 752 2520</a></p>
      <p>Facebook: <a href="https://www.facebook.com/profile.php?id=61555615652631&mibextid=ZbWKwL" target="_blank">Vasta Restaurant</a></p>
      </td>
      </tr>
     </table>
    </div>


     <div>
    <table>
      <tr>
      <td>
      <img src="https://i.pinimg.com/736x/dc/70/7c/dc707c0e2e4a1883d4ebb81d107aec9a.jpg" alt="Vasta Restaurant">
      <h1>Vasta Restaurant</h1>
      <p>Phone Number: <a href="tel:09947522520">0994 752 2520</a></p>
      <p>Instagram: <a href="https://www.instagram.com/vasta_restaurant2023?igsh=bWdnd2U3ZnFnMHVq" target="_blank">vasta_restaurant2023</a></p>
      </td>
      </tr>
     </table>
    </div>



     <div>
    <table>
      <tr>
      <td>
      <img src="file:///D:/Users/Sam%20Andrew%20Osias/Downloads/navales.jpg" alt="Benedict Navales">
      <h1>Benefict Navales</h1>
      <p>Phone Number: <a href="tel:09947522520">0994 752 2520</a></p>
      <p>Email: <a href="mailto:navalesbenedict2@gmail.com">navalesbenedict2@gmail.com</a></p>
      <p>Facebook: <a href="https://www.facebook.com/BenZayb.09?mibextid=hIlR13" target="_blank">Benedict Navales</a></p>
      </td>
      </tr>
     </table>
    </div>


    <div>
     <table>
      <tr>
      <td>
      <img src="IMG_20240111_093526_288.jpg" alt="Limuel Coronel">
      <h1>Limuel Coronel</h1>
      <p>Phone Number: <a href="tel:09152591401">0915 259 1401</a></p>
      <p>Email: <a href="mailto:coronellimuel807@gmail.com">coronellimuel807@gmail.com</a></p>
      <p>Facebook: <a href="https://www.facebook.com/profile.php?id=100076144661336&mibextid=2JQ9oc">Limuel Coronel</a></p>
      </td>
      </tr>
     </table>
    </div>
    
    
    <div>
     <table>
      <tr>
      <td>
      <img src="https://dragon.online-convert.com/download-file/361f178c-caac-4d60-b93e-feff9516d271/564bf9bc-8860-4d54-b586-cdf50a70f488" alt="Joseph Pineda">
      <h1>Joseph Pineda</h1>
      <p>Phone Number: <a href="tel:0994 962 1887">0994 962 1887</a></p>
      <p>Email: <a href="mailto:voozetcodm@gmail.com">voozetcodm@gmail.com</a></p>
      <p>Facebook: <a href="https://www.facebook.com/Sephygwaps8?mibextid=gik2fB">Joseph Pineda</a></p>
      </td>
      </tr>
     </table>
    </div>

    
    <div>
     <table>
      <tr>
      <td>
      <img src="https://dragon.online-convert.com/download-file/4f250ec4-96da-4dfb-bec8-ed8d65d57bb6/660463aa-b314-4949-b2f5-216ffd1a8d4b" alt="Brian Berondo">
      <h1>Brian Berondo</h1>
      <p>Phone Number: <a href="tel:0997 642 4306">0997 642 4306</a></p>
      <p>Email: <a href="mailto:brianberondo7@gmail.com">brianberondo7@gmail.com</a></p>
      <p>Facebook: <a href="https://www.facebook.com/brian.berondo.56?mibextid=ZbWKwL">Brian Berondo</a></p>
      </td>
      </tr>
     </table>
    </div>
    
    
    <div>
     <table>
      <tr>
      <td>
      <img src="https://dragon.online-convert.com/download-file/ddb0514b-8b30-4e87-9cbc-035ffc8a33f6/dd7167dc-6909-4871-bc43-290fa667b289" alt="Kenji Shin Binaya">
      <h1>Kenji Shin Binaya</h1>
      <p>Phone Number: <a href="tel:0968 302 6021">0968 302 6021</a></p>
      <p>Email: <a href="mailto:kenjishinbinaya@gmail.com">kenjishinbinaya@gmail.com</a></p>
      <p>Facebook: <a href="https://www.facebook.com/profile.php?id=100080174755692&mibextid=kFxxJD">Kenji Shin Binaya</a></p>
      </td>
      </tr>
     </table>
    </div> 
<!-- ... (previous code) ... -->

 <table class="table_b">
         <tr>
            <td>
              <form action="your_chat_handler.php" method="post">
          <div>
            <label for="userName">Your Name:</label>
            <input type="text" id="userName" name="userName" required>
          </div>
          <div>
            <label for="userEmail">Your Email:</label>
            <input type="email" id="userEmail" name="userEmail" required>
          </div>
          <div>
            <label for="orderDetailsNumber">Order Details/Number:</label>
            <input type="text" id="orderDetailsNumber" name="orderDetailsNumber" required>
          </div>
          <div>
            <label for="userMessage">Your Message:</label>
            <textarea id="userMessage" name="userMessage" rows="4" required></textarea>
          </div>
          <div>
            <button type="submit">Start Chat</button>
          </div>
        </form>

        <!-- Link to owner's messenger -->
              <p>Prefer to chat directly? <a href="https://m.me/BenZayb.09" target="_blank">Click here to open messenger</a></p>
      </td>
    </tr>
</table>


</div>
</div>

  <script>
    let cartItems = [];

    function addToCart(itemName, price) {
      const cartItem = { name: itemName, price: price };
      cartItems.push(cartItem);

      // Update the cart display
      updateCartDisplay();
    }

    function updateCartDisplay() {
      const cartContainer = document.getElementById('cart-items');
      const totalAmountSpan = document.getElementById('total-amount');

      // Clear the existing content
      cartContainer.innerHTML = '';

      // Update the cart items
      cartItems.forEach(item => {
        const itemDiv = document.createElement('div');
        itemDiv.innerHTML = `<p>${item.name}: Php ${item.price}</p>`;
        cartContainer.appendChild(itemDiv);
      });

      // Update the total amount
      const totalAmount = cartItems.reduce((total, item) => total + item.price, 0);
      totalAmountSpan.textContent = `Php ${totalAmount}`;
    }

    function checkout() {
      // Implement your checkout logic here
      // For example, you can show an alert or redirect to a checkout page
      alert('Checkout completed! Thank you for ordering your Total amount is: Php ' + cartItems.reduce((total, item) => total + item.price, 0));

      // Clear the cart after checkout
      cartItems = [];
      updateCartDisplay();
    }

    // Your existing script for page navigation
    function showPage(pageId) {
      const pages = ['home', 'menu', 'about', 'contact', 'cart'];

      pages.forEach(page => {
        const element = document.getElementById(page);
        if (page === pageId) {
          element.style.display = 'block';
        } else {
          element.style.display = 'none';
        }
      });
    }
  </script>

  <footer>
  
    <h3>&copy; 2023 Vasta Restaurant. All rights reserved.</h3>
  </footer>

</body>

</html>
