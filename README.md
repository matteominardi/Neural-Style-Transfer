<style>
#images {
    white-space: nowrap;
}
</style>

<h2>Re-implemented the Neural Style Transfer paper for educational purposes.</h2>
Every step performed has been completely inspired from the original paper and has been described inside the jupyter notebook as it was being implemented. <br><br>
The program takes in input a content image and a style image. <br> 
The output contains the content of the first picture, styled as if it was inspired by the second one. 
<br><br>
In this example, the content image represents of my favourite areas of my hometowm and the style one is "The Starry Night" by Vincent van Gogh. The final result makes it look like the original picture was in fact made by the artist as if it was one of his paintings.
<br><br>
Obviously, this can be done with any arbitrary input and style image pairs to achieve stunning results.
<hr>
<h3>Content image:</h3> 
<img title="Original content image" width="250px" alt="Alt text" src="content.jpg">
<h3>Style image:</h3> 
<img title="Original style image" width="250px" alt="Alt text" src="style.jpg">
<h3>Results: (after 500, 2000 and 7000 epochs)</h3> 
<img title="Output after 500 epochs" width="250px" alt="Alt text" src="500.png">
<img title="Output after 2000 epochs" width="250px" alt="Alt text" src="2000.png">
<img title="Output after 7000 epochs" width="250px" alt="Alt text" src="7000.png">
<hr>
Feel free to check the files if you wish to see the code or the intermediate resutls.