# image-fill-page-margins
When using Bootstrap containers, your image + text section will by default having padding on either side of it. Often, however, you will want your image to meet the page’s edge without padding.

## Tutorial		  
For detailed instruction's, view Solodev's [How to Make an Image Fill the Page Margins](https://www.solodev.com/blog/how-to-make-an-image-fill-the-page-margins.stml) article.
 
## Demo  		  
Try out a working example on [JSFiddle](https://jsfiddle.net/solodev/9mqw14ka/2/).

## HTML
The tutorial contains the following basic HTML markup.

```
<section class="section-text">
          <div class="picture">
            <img src="https://raw.githubusercontent.com/solodev/image-filling-page-margins/master/images/image.jpg" alt="astronaut" class="img-fluid hidden-xs">
            <img src="https://raw.githubusercontent.com/solodev/image-filling-page-margins/master/images/image-sm.jpg" alt="catstronaut" class="img-fluid visible-xs"> 
          </div>
          <div class="container">
            <div class="row">
              <div class="text-wrapper">
                  <h2 class="mb-0">Be part of the 
                      <span class="font-weight-bold">Lunar XPerience</span>
                   </h2>
                   <p class="my-4">If you're an explorer, then the moon is calling.<br>
                    Join the LunarXP mission where new worlds await.</p>
                <a class="btn btn-primary text-white" href="#" tabindex="0">Tour Our Ships</a> 
              </div><!--.text-wrapper-->
            </div>
          </div><!--.container-->
</section><!--.section-text-->
```

## CSS
All required CSS is contained with style.css

## External Resources
This tutorial includes the following third party resources.

```
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css" integrity="sha384-MCw98/SFnGE8fJT3GXwEOngsV7Zt27NXFoaoApmYm81iuXoPkFOJwJ8ERdknLPMO" crossorigin="anonymous">
<script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/js/bootstrap.min.js" integrity="sha384-ChfqqxuZUCnJSK3+MXmPNIyE6ZbWh2IMqE241rYiqJxyMiZ6OW/JmZQ5stwEULTy" crossorigin="anonymous"></script>
```