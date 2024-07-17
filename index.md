<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Image Gallery</title>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/lightbox2/2.11.3/css/lightbox.min.css" rel="stylesheet">
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 20px;
            display: flex;
            flex-direction: column;
            align-items: center;
        }
        h1 {
            color: #333;
        }
        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
            gap: 20px;
            max-width: 1000px;
            width: 100%;
        }
        .gallery-item {
            position: relative;
            text-align: center;
        }
        .gallery img {
            width: 100%;
            height: auto;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            transition: transform 0.2s;
        }
        .gallery img:hover {
            transform: scale(1.50);
        }
        .caption {
            position: absolute;
            bottom: 8px;
            left: 50%;
            transform: translateX(-50%);
            background-color: rgba(0, 0, 0, 0.5);
            color: white;
            padding: 5px 10px;
            border-radius: 8px;
            font-size: 14px;
        }
    </style>
</head>
<body>
    <h1>Gilbertine Weekend Away - Herefore 2024</h1>
    <p>For the Gilbertine Lab, weekend away 2024, we headed to Hereford to sample the river Wye, through a day of canoeing</p>
    <div class="gallery">
        <div class="gallery-item">
            <a href="images/IMG_5436.jpg" data-lightbox="gallery" data-title="The weekend Logo">
                <img src="images/IMG_5436.jpg" alt="Image 7">
                <div class="caption">The weekend Logo</div>
            </a>
        </div>
        <div class="gallery-item">
            <a href="images/IMG-20240712-WA0003.jpg" data-lightbox="gallery" data-title="On top of the Malvern Hills">        
                <img src="images/IMG-20240712-WA0003.jpg" alt="Image 1">
                <div class="caption">On top of the Malvern Hills</div>
            </a>    
        </div>
        <div class="gallery-item">
            <img src="images/IMG-20240712-WA0007-w.jpg" alt="Image 2">
            <div class="caption">A cow</div>
        </div>
        <div class="gallery-item">
            <img src="images/IMG-20240712-WA0013.jpg" alt="Image 3">
            <div class="caption">Pretty view of Malven Hills</div>
        </div>
        <div class="gallery-item">
            <img src="images/IMG-20240713-WA0001.jpg" alt="Image 4">
            <div class="caption">Conaling on the River Wye</div>
        </div>
        <div class="gallery-item">
            <img src="images/IMG-20240713-WA0003.jpg" alt="Image 6">
            <div class="caption">The Group, with Sadegh and I after jsut capsizing</div>
        </div>        
        <div class="gallery-item">
            <img src="images/IMG-20240713-WA0004.jpg" alt="Image 5">
            <div class="caption">Ed and Xu</div>
        </div>
        <div class="gallery-item">
            <img src="images/IMG-20240713-WA0007.jpg" alt="Image 8">
            <div class="caption">Adrienne and Mona</div>
        </div>
        <div class="gallery-item">
            <img src="images/IMG-20240713-WA0009.jpg" alt="Image 9">
            <div class="caption">Morred up for lunch</div>
        </div>        
        <div class="gallery-item">
            <img src="images/IMG-20240713-WA0013.jpg" alt="Image 5">
            <div class="caption">We did it 11 miles 4.1/2 hours</div>
        </div>
        <div class="gallery-item">
            <img src="images/IMG-20240713-WA0016.jpg" alt="Image 5">
            <div class="caption">Hay on Wye Castle for Lunch</div>
        </div>
        <div class="gallery-item">
            <img src="images/PXL_20240713_195348632.MP.jpg" alt="Image 10">
            <div class="caption">Shedgh and Ed playing Pool</div>
        </div>        
        <div class="gallery-item">
            <img src="images/PXL_20240713_091408242.jpg" alt="Image 8">
            <div class="caption">Paddling</div>
        </div>
        <div class="gallery-item">
            <img src="images/IMG-20240713-WA0008.jpg" alt="Image 8">
            <div class="caption">Flowers</div>
        </div>
        <div class="gallery-item">
            <img src="images/IMG-20240712-WA0001.jpg" alt="Image 9">
            <div class="caption">The tesco</div>
        </div>        
        <div class="gallery-item">
            <img src="images/IMG-20240714-WA0000.jpg" alt="Image 9">
            <div class="caption">Tresure Trail in Hereford</div>
        </div>
        <div class="gallery-item">
            <img src="images/IMG-20240714-WA0003.jpg" alt="Image 9">
            <div class="caption">Edgar and Xu</div>
        </div>
        <div class="gallery-item">
            <img src="images/IMG-20240714-WA0006.jpg.jpg" alt="Image 9">
            <div class="caption">The King Pigeon</div>
        </div>                        
    </div>
    <p>Thank you for visiting the gallery!</p>
</body>
</html>