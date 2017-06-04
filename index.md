## Welcome to mylittlespace

You can use the [editor on GitHub](https://github.com/Just-Have-Fun-X/Just-Have-Fun-X.github.io/edit/master/index.md) to maintain and preview the content for your website in Markdown files.

This is the place where I create to share my daily-life, interesting things……

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

### Jekyll Themes
function moveShadow(){
    lightX          = parseInt(lightbulb.offset().left) + lightCenterX;
    lightY          = parseInt(lightbulb.offset().top) + lightCenterY;
    logoX           = parseInt(logo.offset().left) + logoCenterX;
    logoY           = parseInt(logo.offset().top) + logoCenterY;
    distanceX       = logoX - lightX;
    distanceY       = logoY - lightY;
    distance        = Math.sqrt(Math.pow(distanceX, 2) + Math.pow(distanceY, 2));
    shadowDistance  = distance * shadowOffset;
    shadowPosLeft   = (distanceX / distance * shadowDistance + lightX - logoShdwCenterX) + "px";
    shadowPosTop    = (distanceY / distance * shadowDistance + lightY - logoShdwCenterY) + "px";
    logoshadow.css({ "left": shadowPosLeft, "top": shadowPosTop, "opacity": setOpacity(shadowDistance) });

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
