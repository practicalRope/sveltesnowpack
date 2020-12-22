<style>
  :global(body) {
    margin: 0;
    font-family: Oxygen;
  }

  div {
    height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  span {
    position: absolute;
    color: rgb(255, 51, 0);
    font-weight: bold;
  }
  span:nth-child(1) {
    animation: intro 8s infinite linear;
    font-size: 3rem;
  }
  span:nth-child(2) {
    animation: intro 8.5s infinite linear;
    font-size: 3.1rem;
    opacity: 0.3;
  }

  @keyframes intro {
    to {
      transform: rotateX(360deg) rotateZ(360deg);
    }
  }
</style>

<div>
  <span>TEMPLATE!!!</span>
  <span>TEMPLATE!!!</span>
</div>
