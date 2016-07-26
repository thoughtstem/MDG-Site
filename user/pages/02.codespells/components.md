---
title: CodeSpells
metadata:
  description: CodeSpells
slug: codespells
visible: false
---

<style>
  .avatar{
    -moz-border-radius: 50%;
    -webkit-border-radius: 50%;
    border-radius: 50%;
    width: 30px; 
  }

  .jumbotron .container h1{
    text-shadow: 1px 1px 2px black,0 0 50px #000,0 0 5px black;
  }
  .jumbotron .container h2{
    text-shadow: 1px 1px 2px black,0 0 50px #000,0 0 5px black;
  }
</style>

[g-jumbotron name="jumbotron1" fullwidth="true" image="codespells.jpg" render=false]

# CodeSpells
##Craft magic spells with code

[/g-jumbotron]

[g-well name=well1]
>The coders of today are the wizards of the future.
>>-Gabe Newell
[/g-well]

# Coding is Magic

It's a game where you make your own magic spells by writing code.  Play online with other people or explore a rich single-player sandbox.

CodeSpells began as one of Stephen's Ph.D. research projects.  But [the version now on Steam](http://store.steampowered.com/app/324190/) was completely reimagined by Adrian and Jason.  This was possible because Lindsey ran a [super effective Kickstarter](https://www.kickstarter.com/projects/thoughtstem/codespells-express-yourself-with-magic) for CodeSpells.  And the rest is history.

## A brief history


Before the Kickstarter, Jason did a bunch of cool concept art to craft the vision:

[g-carousel id="carousel1" name=carousel1]

[g-carousel-item image="codespells.jpg"]
A dark fantasy game
[/g-carousel-item]

[g-carousel-item image="water2_flat_cropped.jpg"]
...with elemental magic
[/g-carousel-item]

[g-carousel-item image="stormcasting_cropped.jpg"]
...where your knowledge is power
[/g-carousel-item]

[g-carousel-item image="forrest_cropped.jpg"]
...in a living, breathing world.
[/g-carousel-item]
[/g-carousel]

<br/> 

Then Adrian made playable prototype of Jason's world, adding in scriptable spells.  This allowed Stephen to make a demo video that became our Kickstarter trailer.

<iframe style="float:left; margin: 20px;" width="560" height="315" src="https://www.youtube.com/embed/NN5mQxX-Zd0" frameborder="0" allowfullscreen></iframe>
 
Then Lindsey managed to run a super effective Kickstarter campaign, getting over 5000 backers and netting $160K, more than 3 times the amount of funding we expected.  She leveraged her background as a scientist, doing some [cool data-driven analysis that she has shared with the Gamasutra community](http://www.gamasutra.com/blogs/LindseyHandley/20140930/226640/Lessons_Learned_in_a_Successful_Indie_Game_Kickstarter_Campaign_How_CodeSpells_Raised_120K.php).

## Releasing on Steam

Concurrently with the Kickstarter campaign, Lindsey also ran a Steam Greenlight campaign.  Within 9 days of our Kickstarter campaign, we were greenlit.  So we [released on early access a few months later](http://store.steampowered.com/app/324190/).  This allowed us to design the game while getting feedback from real customers.  We spent many months adding features based on this feedback.

<div style="clear:both"></div>

## Multiplayer

Of all possible features, the one people seem to want most is multiplayer.  So we're currently working on that.  The [version on Steam](http://store.steampowered.com/app/324190/) has a prototype of multiplayer already.  We did [a press release about that](https://codespells.org/press.html).  There are five multiplayer game modes (called Arenas) -- one of which is a cool "Wizard Soccer" Arena.

<iframe style="float:left; margin: 20px;" width="560" height="315" src="https://www.youtube.com/embed/f1zrBNMsAno" frameborder="0" allowfullscreen></iframe>

There has been one [community-run tournament in CodeSpells](http://the-codespells-forum.herokuapp.com/t/the-first-official-codespells-tournament/1573) already.  We're excited to see this kind of thing happening.

However, one current drawback is that CodeSpells multiplayer requires you to forward your ports and exchange your IP address with people you want to invite to your Arenas.  We don't like this.

So Stephen is working on a system that will allow CodeSpells players to start servers in the cloud whenever they want.  Meanwhile Adrian is working on making the multiplayer gameplay more smooth.  And Jason is building more multiplayer arenas, supporting a wider variety of multiplayer experiences.  

<div style="clear:both"></div>

## Creatures

It was Jason's vision to have a world filled with fantastical creatures.  So one of the ongoing efforts is to add more creatures.  This will probably never be finished.  We plan on adding content to CodeSpells forever.

## More Arenas

We want to make CodeSpells into a platform for users to create content too.  (We're a small team; we can't do `all` the work!)  So Adrian is polishing up the tools that he uses to create Arenas.  We'll release these to the CodeSpells community as an in-game interface, allowing anyone to create multiplayer Arenas and share them with others.  Meanwhile Jason will make various Arena "starter environments" and assets and release them to the community.  


<script>
 $(document).ready(function(){
   $("p").each(function(i,e){
     $(e).html($(e).html().replace(/Stephen /g,"<img src='/images/stephen-avatar.jpg' class='avatar'></img> Stephen "))  
     $(e).html($(e).html().replace(/Adrian /g,"<img src='/images/adrian-avatar.jpg' class='avatar'></img> Adrian "))  
     $(e).html($(e).html().replace(/Jason /g,"<img src='/images/jason-avatar.jpg' class='avatar'></img> Jason "))  
     $(e).html($(e).html().replace(/Lindsey /g,"<img src='/images/lindsey-avatar.jpg' class='avatar'></img> Lindsey "))  
   }) 
 })
</script>


## Interested?



<!-- Begin MailChimp Signup Form -->
<link href="//cdn-images.mailchimp.com/embedcode/classic-10_7.css" rel="stylesheet" type="text/css">
<style type="text/css">
	#mc_embed_signup{background:#fff; clear:left; font:14px Helvetica,Arial,sans-serif; }
	/* Add your own MailChimp form style overrides in your site stylesheet or in this style block.
	   We recommend moving this block and the preceding CSS link to the HEAD of your HTML file. */
</style>
<div id="mc_embed_signup">
<form action="//thoughtstem.us7.list-manage.com/subscribe/post?u=ba289778d383282a18af8d30a&amp;id=0a88723493" method="post" id="mc-embedded-subscribe-form" name="mc-embedded-subscribe-form" class="validate" target="_blank" novalidate>
    <div id="mc_embed_signup_scroll">
	<h2>Subscribe to our mailing list</h2>
<div class="indicates-required"><span class="asterisk">*</span> indicates required</div>
<div class="mc-field-group">
	<label for="mce-EMAIL">Email Address  <span class="asterisk">*</span>
</label>
	<input type="email" value="" name="EMAIL" class="required email" id="mce-EMAIL">
</div>
<div class="mc-field-group">
	<label for="mce-FNAME">First Name </label>
	<input type="text" value="" name="FNAME" class="" id="mce-FNAME">
</div>
<div class="mc-field-group">
	<label for="mce-LNAME">Last Name </label>
	<input type="text" value="" name="LNAME" class="" id="mce-LNAME">
</div>
<div class="mc-field-group input-group">
    <strong>Are you interested in CodeSpells? </strong>
    <ul><li><input type="radio" value="Yes" name="CODESPELLS" id="mce-CODESPELLS-0"><label for="mce-CODESPELLS-0">Yes</label></li>
<li><input type="radio" value="No" name="CODESPELLS" id="mce-CODESPELLS-1"><label for="mce-CODESPELLS-1">No</label></li>
</ul>
</div>
<div class="mc-field-group input-group">
    <strong>Are you interested in Vox-L? </strong>
    <ul><li><input type="radio" value="Yes" name="VOXL" id="mce-VOXL-0"><label for="mce-VOXL-0">Yes</label></li>
<li><input type="radio" value="No" name="VOXL" id="mce-VOXL-1"><label for="mce-VOXL-1">No</label></li>
</ul>
</div>
<div class="mc-field-group input-group">
    <strong>Are you interested in LearnToMod? </strong>
    <ul><li><input type="radio" value="Yes" name="LEARNTOMOD" id="mce-LEARNTOMOD-0"><label for="mce-LEARNTOMOD-0">Yes</label></li>
<li><input type="radio" value="No" name="LEARNTOMOD" id="mce-LEARNTOMOD-1"><label for="mce-LEARNTOMOD-1">No</label></li>
</ul>
</div>
<div class="mc-field-group input-group">
    <strong>Are you interested in The Planes? </strong>
    <ul><li><input type="radio" value="Yes" name="PLANES" id="mce-PLANES-0"><label for="mce-PLANES-0">Yes</label></li>
<li><input type="radio" value="No" name="PLANES" id="mce-PLANES-1"><label for="mce-PLANES-1">No</label></li>
</ul>
</div>
<div class="mc-field-group input-group">
    <strong>Are you interested in Torb? </strong>
    <ul><li><input type="radio" value="Yes" name="TORB" id="mce-TORB-0"><label for="mce-TORB-0">Yes</label></li>
<li><input type="radio" value="No" name="TORB" id="mce-TORB-1"><label for="mce-TORB-1">No</label></li>
</ul>
</div>
	<div id="mce-responses" class="clear">
		<div class="response" id="mce-error-response" style="display:none"></div>
		<div class="response" id="mce-success-response" style="display:none"></div>
	</div>    <!-- real people should not fill this in and expect good things - do not remove this or risk form bot signups-->
    <div style="position: absolute; left: -5000px;" aria-hidden="true"><input type="text" name="b_ba289778d383282a18af8d30a_0a88723493" tabindex="-1" value=""></div>
    <div class="clear"><input type="submit" value="Subscribe" name="subscribe" id="mc-embedded-subscribe" class="button"></div>
    </div>
</form>
</div>
<script type='text/javascript' src='//s3.amazonaws.com/downloads.mailchimp.com/js/mc-validate.js'></script><script type='text/javascript'>(function($) {window.fnames = new Array(); window.ftypes = new Array();fnames[0]='EMAIL';ftypes[0]='email';fnames[1]='FNAME';ftypes[1]='text';fnames[2]='LNAME';ftypes[2]='text';fnames[3]='CODESPELLS';ftypes[3]='radio';fnames[4]='VOXL';ftypes[4]='radio';fnames[5]='LEARNTOMOD';ftypes[5]='radio';fnames[6]='PLANES';ftypes[6]='radio';fnames[7]='TORB';ftypes[7]='radio';}(jQuery));var $mcj = jQuery.noConflict(true);</script>
<!--End mc_embed_signup-->

