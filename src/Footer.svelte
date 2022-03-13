<footer>
  <div>
    <h2>SERVICES</h2>
    <ul>
      <li>Branding</li>
      <li>Design</li>
      <li>Marketing</li>
      <li>Advertisement</li>
    </ul>
  </div>
  <div>
    <h2>COMPANY</h2>
    <ul>
      <li>About us</li>
      <li>Contact</li>
      <li>Jobs</li>
      <li>Press kit</li>
    </ul>
  </div>

  <div>
    <h2>LEGAL</h2>
    <ul>
      <li>Terms of use</li>
      <li>Privacy policy</li>
      <li>Cookie policy</li>
    </ul>
  </div>
</footer>

<style>
  footer {
    width: 100%;
    height: auto;
    display: grid;
    align-items: flex-start;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    background-color: var(--default-color);
    font-family: var(--primary-font);
  }
  div {
    display: flex;
    flex-direction: column;
    width: 10rem;
    padding-left: 3rem;
    padding-top: 2rem;
    padding-bottom: 2rem;
  }
  h2 {
    color: #a5a8ad;
    font-size: 14px;
    margin-bottom: 1rem;
  }
  ul {
    margin: 0;
    list-style: none;
    padding: 0;
  }
  li {
    color: #ecedee;
    font-size: 12px;
    margin-bottom: 0.6rem;
  }
</style>
