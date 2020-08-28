<style>
  .subheading {
    --mediumdark: '#999999';
    font-weight: 900;
    font-size: 13px;
    color: #999;
    letter-spacing: 6px;
    line-height: 24px;
    text-transform: uppercase;
    margin-bottom: 12px;
    margin-top: 40px;
  }

  .link-list {
    display: grid;
    grid-template-columns: 1fr;
    grid-template-rows: 1fr 1fr;
    row-gap: 10px;
  }

  @media (min-width: 620px) {
    .link-list {
      row-gap: 20px;
      column-gap: 20px;
      grid-template-columns: 1fr 1fr;
    }
  }

  @media all and (-ms-high-contrast:none) {
  .link-list {
      display: -ms-grid;
      -ms-grid-columns: 1fr 1fr;
      -ms-grid-rows: 1fr 1fr;
    }
  }

  .link-item {
    display: block;
    padding: 20px 30px 20px 15px;
    border: 1px solid #00000010;
    border-radius: 5px;
    transition: background 150ms ease-out, border 150ms ease-out, transform 150ms ease-out;
    color: #333333;
    background-color: #ffffff;
    display: flex;
    align-items: flex-start;
  }

  .link-item:hover {
    border-color: #1EA7FD50;
    transform: translate3d(0, -3px, 0);
    box-shadow: rgba(0, 0, 0, 0.08) 0 3px 10px 0;
  }

  .link-item:active {
    border-color: #1EA7FD;
    transform: translate3d(0, 0, 0);
  }

  .link-item strong {
    font-weight: 700;
    display: block;
    margin-bottom: 2px;
  }
  
  .link-item img {
    height: 40px;
    width: 40px;
    margin-right: 15px;
    flex: none;
  }

  .link-item span {
    font-size: 14px;
    line-height: 20px;
  }

  .tip {
    display: inline-block;
    border-radius: 1em;
    font-size: 11px;
    line-height: 12px;
    font-weight: 700;
    background: #E7FDD8;
    color: #66BF3C;
    padding: 4px 12px;
    margin-right: 10px;
    vertical-align: top;
  }

  .tip-wrapper {
    font-size: 13px;
    line-height: 20px;
    margin-top: 40px;
    margin-bottom: 40px;
  }

  .tip-wrapper code {
    font-size: 12px;
    display: inline-block;
  }
</style>

# use-constant-emoji

<img src="./screenshot/README_BANNER.png">

<div class="subheading">Contributing to the project</div>
<div class="link-list">
  <a class="link-item" href="https://github.com/0xBono/use-constant-emoji/issues" target="_blank">
    <span>
      <strong>Project Issues</strong>
      Please contribute by leaving an issue!
    </span>
  </a>
    <a class="link-item" href="https://github.com/0xBono/use-constant-emoji/pulls" target="_blank">
    <span>
      <strong>Project Pull Request</strong>
      Please contribute to the project through PR!
    </span>
  </a>
</div>

<div class="subheading">Contents</div>

Now stop the uncomfortable behavior that bothered you to find an emoji!  
Now you can simply load emojis with one module and make them known to anyone.  


<div class="subheading">installation</div>

~~~bash
### Yarn
yarn add use-constant-emoji

### Npm
npm install use-constant-emoji
~~~

After installation, go to the project to be applied and do the following.

~~~javascript
import { EXAMPLE_EMOJI } from 'use-constant-emoji'
~~~


<div class="subheading">License</div>

This project is freely available to everyone under the [**MIT**](https://github.com/0xBono/use-constant-emoji/blob/master/LICENSE) icense.
