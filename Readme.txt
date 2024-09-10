Thanks for viewing.

Profile Name: MyPortfolio
Live URL:
Author: Al Faysal Bin Asad



//Codes for glow effect

@keyframes flicker {
  0% {
    opacity: 0.7; /* Start with slightly reduced opacity */
  }
  100% {
    opacity: 1; /* End with full opacity */
  }
}

@keyframes glow {
  0% {
    text-shadow: 0 0 10px #00000000; /* Start with no glow effect */
  }
  50% {
    text-shadow: 0 0 20px #09958e, 0 0 30px #09958e, 0 0 40px #09958e,
      0 0 50px #09958e; /* Middle with orange glow */
  }
  100% {
    text-shadow: 0 0 20px #ff0000, 0 0 30px #ff0000, 0 0 40px #ff0000,
      0 0 50px #ff0000; /* End with red glow */
  }
}