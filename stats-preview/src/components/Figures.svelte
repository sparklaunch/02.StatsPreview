<div id="figures">
  <div id="companies">
    <p>10k+</p>
    <p>COMPANIES</p>
  </div>
  <div id="templates">
    <p>314</p>
    <p>TEMPLATES</p>
  </div>
  <div id="queries">
    <p>12M+</p>
    <p>QUERIES</p>
  </div>
</div>

<style>
  #figures {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
  }
  #figures > div > p:first-child {
    color: white;
    font-family: "Inter", sans-serif;
    font-weight: 700;
    font-size: 22px;
    margin-bottom: 5px;
  }
  #figures > div > p:last-child {
    color: rgb(159, 157, 183);
    font-family: "Lexend Deca", sans-serif;
    font-size: 12px;
  }
  @media screen and (max-width: 1440px) {
    #figures {
      display: flex;
      flex-direction: column;
      align-items: center;
    }
    #figures > div {
      margin-bottom: 30px;
    }
    #figures > div > p {
      text-align: center;
    }
  }
</style>
