# GrayScale Conversion

<a href="GrayFilter/ba.jpg"><img src="GrayFilter/ba.jpg" title=""/></a><a href="GrayFilter/answer.png"><img src="GrayFilter/answer.png" title=""/></a>


In order to convert a color image to Grayscale image, you need to read pixels or data of the image using File and ImageIO objects, and store the image in BufferedImage object. Its syntax is given below

```

			BufferedImage source_img;
			try {
				source_img = ImageIO.read(new File("/Users/dabbaghie/eclipse-workspace/GrayFilter/ba.jpg"));
				ImageIO.write(image_result, "PNG", new File("answer.png"));
			
			} catch (IOException e) {
				// TODO Auto-generated catch block
				e.printStackTrace();
			}
```
