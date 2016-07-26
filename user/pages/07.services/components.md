---
title: Services
metadata:
  description: Services
slug: services
visible: false
---

<style>
  .avatar{
    -moz-border-radius: 50%;
    -webkit-border-radius: 50%;
    border-radius: 50%;
    width: 30px; 
  }

  .jumbotron{
    background-color: black;
  }

  .jumbotron .container h1{
    text-shadow: 1px 1px 2px black,0 0 50px #000,0 0 5px black;
  }
  .jumbotron .container h2{
    text-shadow: 1px 1px 2px black,0 0 50px #000,0 0 5px black;
  }
</style>

[g-jumbotron name="jumbotron1" fullwidth="true" image="" render=false]

# Services
##(Your game here)

[/g-jumbotron]

#Bringing your ideas to life

We like bringing ideas to life, whether they're ours or yours.

Adrian has been coding indie games for more than a decade.

Jason is the best digital painter and 3D modeler you'll ever see.

Stephen literally got his Ph.D. in video games.

Lindsey is an expert in fundraising and marketing for indie games.

We give great consultation services.  We also (occasionally) build prototypes for people -- the kind of thing you can use to raise funding for your next phase of game development.  Contact us if you want to chat.

You can email Stephen at: stephen [at-sign] thoughtstem [dot-thing] com

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
