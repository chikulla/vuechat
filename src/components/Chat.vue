<template>
  <div class="container-fluid">
    <div class="row">
      <div class="col-10 bg-light balloon-left">
        After a mild pulmonary infection, tended too little and too late, had suddenly turned into a severe pneumonia that took its toll of my entire body and laid me up for at least three months at nearby Wels, which has a hospital renowned in the field of so-called internal medicine, I accepted an invitation from Hoeller, a so-called taxidermist in the Aurach valley, not for the end of October, as the doctors urged, but for early in October, as I insisted, and then went on my own so-called responsibility straight to the Aurach valley and to Hoeller’s house, without even a detour to visit my parents in Stocket, straight into the so-called Hoeller garret, to begin sifting and perhaps even arranging the literary remains of my friend, who was also a friend of the taxidermist Hoeller, Roithamer, after Roithamer’s suicide, I went to work sifting and sorting the papers he had willed to me, consisting of thousands of slips covered with Roithamer’s handwriting plus a bulky manuscript entitled “About Altensam and everything connected with Altensam, with special attention to the Cone.
      </div>
      <div class="col-2">
      </div>
    </div>

    <div class="row">
      <div class="col-2">
      </div>
      <div class="col-10 text-white bg-primary balloon-right">
        I replied long sentence.
      </div>
    </div>

    <div class="row">
      <div class="col-10 bg-light balloon-left">
        He said something.
      </div>
      <div class="col-2">
      </div>
    </div>

    <div class="row empty">
    </div>

    <form class="fixed-bottom">
      <div class="input-group">
        <input type="text"
               class="form-control rounded-0"
               placeholder="Input message here...">
        <span class="input-group-btn">
          <button class="btn btn-primary rounded-0">
            <i class="fa fa-send"></i>
            Send
          </button>
        </span>
      </div>
    </form>
  </div>
</template>

<script>
  export default {
    name: 'Chat',
    data () {
      return {
        msg: 'Welcome to Vue'
      }
    }
  }
</script>

<style scoped>
  .balloon-right, .balloon-left {
    margin-top: 0.6rem;
  }
  .empty {
    height: 3rem;
  }
</style>
