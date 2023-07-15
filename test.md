---
layout: single
author_profile: false
---
@keyframes floatDNA {
  0% {
    transform: translateY(0) rotate(0deg);
  }
  50% {
    transform: translateY(-50px) rotate(180deg);
  }
  100% {
    transform: translateY(0) rotate(360deg);
  }
}

.dna {
  width: 50px;
  height: 100px;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  background-image: linear-gradient(to right, red, blue);
  border-radius: 50%;
  animation-name: floatDNA;
  animation-duration: 3s;
  animation-timing-function: linear;
  animation-iteration-count: infinite;
}