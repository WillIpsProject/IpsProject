<template>
  <div id="app">
    <h1 class="heading">10 Best Photo Apps For Incredible iPhone Photography (2020 Edition)</h1>
    <hr class="divider">
    <p class="intro">How do you capture more interesting travel photos with your iPhone? How do you aboid taking the same cliché vacation photos that everyone else that everone else takes? I recently interviewed Steffen Geldner - a talented iPhone photographer with a passion for travel. In this article, Steffen reveals 7 tips for shooting beautiful travel photos that will preserve the amazing memories of your trip. Read on to discover how to take better travel photos with your iPhone!</p>
    <button class="send-tips-btn"><p class="send-tips-btn__text">Send Me The Tips</p></button>
    <img src="/assets/IpsImage.png">
    <h2 class="tip-heading tip-1-heading">1. Research Your Destination To Find The Best Photo Opportunties</h2>
    <p class="tip-content tip-1-content">Before your trip, I reccomend researching the destination to find the most interesting photo opportunities. <br> <br> I always research the location I'm traveling to. I do this extensively and obsessively! <br> <br> It's up to you how much research you do. But you should definately spend a bit of time looking up some great places to take pictures. <br> <br> So, what kind of research can you do? <br> <br> First, you could seach for photos that other people have taken at the locations you're planning to visit. <br> <br> Search on Instagram or Google to get an idea of the kinds of photos people take there.</p>
    <h2 class="tip-heading tip-2-heading">2. Capture Your Journey To Tell The Complete Story Of Your Travels</h2>
    <p class="tip-content tip-2-content">Travel photography isn't just about photographing the destination. <br> <br> For a more complete photographic story, capture your hourney to and from the location you're visiting. <br> <br> If you're traveling by plane, try to get a window seat where you have a view of the wing or properller. <br> <br> And of course, you could capture a beautiful aerial view of clouds, mountains, or city lights as you're flying above. Your journey will often involve several different types of transport. And they all offer great photo opportunities. <br> <br> Whether you're traveling by car, taxi, bus, train, boat, or plane, try to capture some interesting photos.</p>
  </div>
</template>

<script>

export default {
  name: 'App',
  components: {
  }
}
</script>

<style>
.heading {
  position: absolute;
  width: 560px;
  height: 62px;
  left: 267px;
  top: 76px;

  font-family: Lato;
  font-style: normal;
  font-weight: bold;
  font-size: 26px;
  line-height: 31px;

  color: #101010;
}

.divider {
  position: absolute;
  width: 561px;
  height: 1px;
  left: 267px;
  top: 154px;
  border-top: 3px solid #b32066;
}

.intro {
  position: absolute;
  width: 560px;
  height: 144px;
  left: 267px;
  top: 183px;

  font-family: Lato;
  font-style: normal;
  font-weight: 300;
  font-size: 16px;
  line-height: 24px;
  /* or 150% */


  color: #101010;
}

.send-tips-btn {
position: absolute;
width: 220px;
height: 40px;
left: 922px;
top: 204px;
background: linear-gradient(90deg, #AC519C 0.83%, #E5424F 100%);
}

.send-tips-btn__text {
  font-family: Lato;
  font-style: normal;
  font-weight: bold;
  font-size: 15px;
  /* identical to box height */

text-align: center;

color: #FFFFFF;
}

.tip-heading {
  position: absolute;
  width: 560px;
  height: 49px;
  

  font-family: Lato;
  font-style: normal;
  font-weight: bold;
  font-size: 18px;
  line-height: 22px;

  color: #101010;
}

.tip-1-heading {
  left: 267px;
  top: 730px;
}

.tip-2-heading {
  left: 267px;
  top: 1145px;
}

.tip-content {
  position: absolute;
  width: 560px;
  height: 354px;

  font-family: Lato;
  font-style: normal;
  font-weight: 300;
  font-size: 16px;
  line-height: 24px;
  /* or 150% */


  color: #101010;
}

.tip-1-content {
  left: 267px;
  top: 771px;
}

.tip-2-content {
  left: 267px;
  top: 1186px;
}
</style>
