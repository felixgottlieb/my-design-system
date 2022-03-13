<script>
  import Button from "./Button.svelte";
  import Badge from "./Badge.svelte";
  import Footer from "./Footer.svelte";
  import Card from "./Card.svelte";
  import Avatar from "./Avatar.svelte";
  import Buttonwithbadge from "./Buttonwithbadge.svelte";
  import Avatarwithicon from "./Avatarwithicon.svelte";
</script>

<header><h1>Design System</h1></header>
<main>
  <div class="component-container">
    <h2 id="div-title">Buttons</h2>

    <div class="component">
      <Button>BUTTON</Button>
      <pre><code>&lt;Button&gt;BUTTON&lt;Button&gt;</code></pre>
      <div id="underline-div" />
    </div>
    <div class="component">
      <Button type="primary">PRIMARY</Button>
      <pre><code>&lt;Button type="primary"&gt;PRIMARY&lt;Button&gt;</code></pre>
      <div id="underline-div" />
    </div>
    <div class="component">
      <Button type="secondary">SECONDARY</Button>
      <pre><code>&lt;Button type="secondary"&gt;SCEONDARY&lt;Button&gt;</code
        ></pre>
      <div id="underline-div" />
    </div>
    <div class="component">
      <Button type="accent">ACCENT</Button>
      <pre><code>&lt;Button type="accent"&gt;ACCENT&lt;Button&gt;</code></pre>
      <div id="underline-div" />
    </div>
    <div class="component">
      <Button type="ghost">GHOST</Button>
      <pre><code>&lt;Button type="ghost"&gt;GHOST&lt;Button&gt;</code></pre>
      <div id="underline-div" />
    </div>
    <div class="component">
      <Button type="link">LINK</Button>
      <pre><code>&lt;Button type="link"&gt;LINK&lt;Button&gt;</code></pre>
    </div>

    <div id="underline" />
  </div>
  <div class="component-container">
    <h2 id="div-title">Badges</h2>
    <div class="component">
      <Badge>neutral</Badge>
      <pre><code>&lt;Badge&gt;neutral&lt;Badge&gt;</code></pre>
      <div id="underline-div" />
    </div>
    <div class="component">
      <Badge type="primary">primary</Badge>
      <pre><code>&lt;Badge type="primary"&gt;primary&lt;Badge&gt;</code></pre>
      <div id="underline-div" />
    </div>
    <div class="component">
      <Badge type="secondary">secondary</Badge>
      <pre><code>&lt;Badge type="secondary"&gt;secondary&lt;Badge&gt;</code
        ></pre>
      <div id="underline-div" />
    </div>
    <div class="component">
      <Badge type="accent">accent</Badge>
      <pre><code>&lt;Badge type="accent"&gt;accent&lt;Badge&gt;</code></pre>
      <div id="underline-div" />
    </div>
    <div class="component">
      <Badge type="ghost">ghost</Badge>
      <pre><code>&lt;Badge type="ghost"&gt;ghost&lt;Badge&gt;</code></pre>
    </div>
    <div id="underline" />
  </div>

  <div class="component-container">
    <h2 id="div-title">Button with badge</h2>
    <div class="component">
      <Buttonwithbadge />
    </div>
    <div class="component">
      <pre class="with-props"><code>&lt;Buttonwithbadge /&gt;</code></pre>
    </div>
    <div id="underline" />
  </div>

  <div class="component-container">
    <h2 id="div-title">Card</h2>
    <div class="component">
      <Card />
      <pre><code>&lt;Card /&gt;</code></pre>
    </div>
    <div id="underline" />
  </div>
  <div class="component-container">
    <h2 id="div-title">Avatars</h2>
    <div class="component">
      <Avatar type="XL">K</Avatar>
      <pre><code>&lt;Avatar type="XL"&gt;K&lt;Avatar&gt;</code></pre>
      <div id="underline-div" />
    </div>
    <div class="component">
      <Avatarwithicon type="w-badge">AK</Avatarwithicon>
    </div>
    <div class="component">
      <pre><code
          >&lt;Avatarwithicon type="w-badge"&gt;AK&lt;Avatarwithicon&gt;</code
        ></pre>
      <div id="underline-div" />
    </div>
    <div class="component">
      <Avatar type="M">MX</Avatar>
      <pre><code>&lt;Avatar type="MX"&gt;MX&lt;Avatar&gt;</code></pre>
      <div id="underline-div" />
    </div>

    <div class="component">
      <Avatar type="S">AA</Avatar>
      <pre><code>&lt;Avatar type="S"&gt;AA&lt;Avatar&gt;</code></pre>
    </div>
    <div id="underline" />
  </div>

  <div class="component-container">
    <h2 id="div-title">Footer</h2>

    <Footer />
    <pre><code>&lt;Footer /&gt;</code></pre>
  </div>
  <p id="footer-text">By Felix Gottlieb</p>
</main>
