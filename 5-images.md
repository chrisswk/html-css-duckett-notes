I.  Images
	A.  1.  Might want to : include images in your web page using HTML
		2.  Pick which image format to use
		3.  Show an image at the right size.
		4.  Optimize an image for use on the web to make pages load faster.
		5.  You can also use CSS to include images in your pages using the background-image-property
	B.  Choosing images for your site
		1.  Images can set the tone for a site in less time than it takes to read a description.
		2.  A page with several images(team members, product photographs) looks better on a consistent background
		3.  Images should:
			a.  Be relevant.
			b.  Convey information
			c.  Convey the right mood
			d.  Be instantly recognizable
			e.  Fit the color palette
		4.  Stock photos:
			www.istockphoto.com
			www.gettyimages.com
			www.veer.com
			www.sxc.hu
			www.fotolia.com
	C.  Storing images on your site
		1.  If built from scratch, it is good practice to create a folder for all images
		2.  As website grows, keeping images in a separate folder helps you understand site organization.
		3.  Maybe use subfolders to the image folder.
		4.  Content management systems usually have tools built into admin site that allows image uploading.
	D.  <img>
		1.  Must carry: src and alt attributes
		2.  Can use title attribute.  Most browsers will display the content when the user hovers ove rthe image.
		3.  Alt should give an accurate description of the image content so it can be understood by screen reader software.  If the image is strictly aesthetic, then the alt attribute is still necessary but should have empty quotes ""
	E.  Height and width of images
		1.  Attributes height, width specify ibid in pixels
		2.  Good idea to specify image size so rest of web page can be rendered while leaving the right amount of space for image.
		3.  Size of images is increasingly specified by CSS rather than HTML.
	F.  Where to place images in your code
		1.  Before, inside the start of and the middle of a paragraph.
			a.  Block elements always appear on a new line.  So if img is followed by a block element, block level wlements will sit on a new line after the image.
			b.  Inline elements sit within a block levle element and do not start on a new line.  Examples include <b>, <em> and <img> elements.  If inside a block level element, any text or other inline elements will flow around the image.
	G.  Old Code: Aliginging images horizontally.
		1.  align attribute: not part of HTML5.
		2.  Likely to come across with old code, some visual editors use it.
		3.  Values: left, right
	H.  Old Code: Aligning images vertically.
		1.  Deprecated, not part of HTML5.
		2.  Values: top, middle, bottom
	I.  Three rules for creating images:
		1.  Save images in the right format: wrong format might not look as sharp as it should and can make pages load slowly
		2.  Save images at the right size.
		3.  Measure images in pixels.
		4.  Editing tools: Adobe Photoshop, Gimp, Pixelmator, Paintshop Pro, Paint.net
	J.  Image formats
		1.  Jpeg: For whenever you have many different colors in a photograph.  Might all be the same general color but have many subtly different shades.
		2.  Gif or png: When saving images with few colors or large areas of the same color.
	K.  Image dimensions:
		1.  Should be saved at the same width and height that you want them to appear on your webpage.
		2.  Cropping images: Don't lose valuable information.  It is best to source images that are the correct shape if possible.
	L.  Measuring images and resolution:  When sizing an image for use on the screen, set dimensions of the image in terms of pixels, not cm or inches
		1.  Save images at 300 dots per inch(DPI) or higher for print.  On the web it is irrelevant.
		2.  Screens determine the size of an image based solely on height and width in pixels.  Not the 72 pixel per inch(PPI) rule of thumb
	M.  Vector images: different from bitmap images, resolution independent.  Commonly created in Adobe Illustrator.
		1.  Line drawings, like the World Wildlife Foundation logo.
		2.  Very different from bitmap images.  Created by placing points on a grid, drawing lines between points.  A color can then be added to fill in the lines created.
		3.  Can increase dimensions without affecting the quality.
		4.  Current method for web: save bitmap version of original vector image, use it.
		5.  Scalable vector graphics(SVG) are a relatively new format used to display vector images directly on the web(eliminating the need to create bitmap versions of them)
			a.  not widespread.
	N.  Animated GIFs
		1.  Show several frames of an image in sequence, good for simple animations.
		2.  Remember: Each frame increases the size of a file, adds to download time.
		3.  Only suitable for simple illustrations.
		4.  Frowned on because they remember a lot of amateur web designers overusing them in the 90s.
	O.  Transparency
		1.  Pick one of two formats: GIF or PNG
			a.  Transparent GIF: Straight edges, 100% transparent(not semi opaque)
			b.  PNG: Diagonal or rounded edges, semi transparent or drop shadowed.
		2.  Not fully supported in older browsers, most notably IE6.  Javascript can get around that.
	P.  Examining images on the web
		1.  Check their size
	Q.  <figure> and <figcaption>
		1.  HTML5: Contains images and their caption so that the two are associated.
		2.  you can have more than one image inside the figure element as long as they all share the same caption.
		3.  Simply ignored by older browsers that do not understand HTML5 elements.
		4. Example:
			<figure>
				<img src="image.jpg" alt="Photograph of something" />
				<br />
				<figcaption>Caption</figcaption>
			</figure>
			