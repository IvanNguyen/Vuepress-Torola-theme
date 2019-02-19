<template>
  <nav class="navigation">
    <ul>
      <li class="has-mega-menu">
        <a href="#">Home</a>
        <div class="mega-menu row flex-wrap">
          <div class="col">
            <ul>
              <li>
                <a href="#">Default</a>
              </li>
              <li>
                <a href="#">Masonry Cards</a>
              </li>
              <li>
                <a href="#">Grid</a>
              </li>
              <li>
                <a href="#">Horizontal</a>
              </li>
              <li>
                <a href="#">Reveal Sections</a>
              </li>
              <li>
                <a href="#">Split</a>
              </li>
              <li>
                <a href="#">Photography</a>
              </li>
            </ul>
          </div>
          <div class="col">
            <ul>
              <li>
                <a href="#" class="new">Onepage Personal</a>
              </li>
              <li>
                <a href="#">Hover List</a>
              </li>
              <li>
                <a href="#">Hover Grid</a>
              </li>
              <li>
                <a href="#">Thumbnail Videos</a>
              </li>
              <li>
                <a href="#">mySlider Thumbnails</a>
              </li>
              <li>
                <a href="#">Horizontal With Title</a>
              </li>
              <li>
                <a href="#">Portfolio With Background</a>
              </li>
            </ul>
          </div>
          <div class="col">
            <ul>
              <li>
                <a href="#" class="new">Onepage Agency</a>
              </li>
              <li>
                <a href="#">Entrance Image</a>
              </li>
              <li>
                <a href="#">Entrance Video</a>
              </li>
              <li>
                <a href="#">Justified</a>
              </li>
              <li>
                <a href="#">Kenburns</a>
              </li>
              <li>
                <a href="#">Parallax Hero</a>
              </li>
            </ul>
          </div>
          <div class="col">
            <ul>
              <li>
                <a href="#">Single Image</a>
              </li>
              <li>
                <a href="#">Single Video</a>
              </li>
              <li>
                <a href="#">Classic Portfolio</a>
              </li>
              <li>
                <a href="#">Fullscreen mySlider</a>
              </li>
              <li>
                <a href="#">Vertical mySlider</a>
              </li>
              <li>
                <a href="#">Parallax Sections</a>
              </li>
            </ul>
          </div>
        </div>
      </li>

      <li>
        <a href="#">About</a>
        <ul>
          <li>
            <a href="#">About Us</a>
          </li>
          <li>
            <a href="#">About Me</a>
          </li>
          <li>
            <a href="#">About Minimal</a>
          </li>
        </ul>
      </li>

      <li class="has-mega-menu">
        <a href="#">Portfolio</a>
        <div class="mega-menu row flex-wrap">
          <div class="col">
            <h6 class="col-title">Portfolios</h6>
            <ul>
              <li>
                <a href="#" class="new">Filterable</a>
              </li>
              <li>
                <a href="#">3 Columns</a>
              </li>
              <li>
                <a href="#">2 Columns</a>
              </li>
              <li>
                <a href="#">4 Columns</a>
              </li>
              <li>
                <a href="#">Portrait</a>
              </li>
              <li>
                <a href="#">Wide</a>
              </li>
              <li>
                <a href="#">Wide 2</a>
              </li>
              <li>
                <a href="#">Metro</a>
              </li>
              <li>
                <a href="#">Masonry Cards</a>
              </li>
            </ul>
          </div>
          <div class="col">
            <h6 class="col-title">Portfolios</h6>
            <ul>
              <li>
                <a href="#">2 Columns Boxed</a>
              </li>
              <li>
                <a href="#">3 Columns Boxed</a>
              </li>
              <li>
                <a href="#">Justified</a>
              </li>
              <li>
                <a href="#">Justified Small</a>
              </li>
              <li>
                <a href="#">Parallax</a>
              </li>
              <li>
                <a href="#">Hover Grid</a>
              </li>
              <li>
                <a href="#">Hover List</a>
              </li>
              <li>
                <a href="#">Horizontal</a>
              </li>
            </ul>
          </div>
          <div class="col">
            <h6 class="col-title">Single Project</h6>
            <ul>
              <li>
                <a href="#">Style 1</a>
              </li>
              <li>
                <a href="#">Style 2</a>
              </li>
              <li>
                <a href="#">Style 3</a>
              </li>
              <li>
                <a href="#">Style 4</a>
              </li>
              <li>
                <a href="#">Style 5</a>
              </li>
              <li>
                <a href="#">Style 6</a>
              </li>
              <li>
                <a href="#">Style 7</a>
              </li>
              <li>
                <a href="#">Style 8</a>
              </li>
            </ul>
          </div>
        </div>
      </li>

      <li>
        <a href="#">Blog</a>
        <ul>
          <li>
            <a href="#">Blog Masonry Boxed</a>
          </li>
          <li>
            <a href="#">Blog Masonry Fullwidth</a>
          </li>
          <li>
            <a href="#">Blog Classic</a>
          </li>
          <li>
            <a href="#">Blog With Sidebar</a>
          </li>
          <li>
            <a href="#">Blog Post</a>
          </li>
        </ul>
      </li>

      <li>
        <a href="#">Contact</a>
        <ul>
          <li>
            <a href="#">Contact Us</a>
          </li>
          <li>
            <a href="#">Contact Me</a>
          </li>
          <li>
            <a href="#">Contact Minimal</a>
          </li>
        </ul>
      </li>
    </ul>
  </nav>
</template>

<script>
export default {};
</script>

<style lang="scss">
.navigation {
  display: block;
  height: 100%;
  /* align-self: stretch; */
  > ul {
    list-style: none;
    margin-bottom: 0;
    height: 100%;
    > li {
      display: inline-block;
      position: relative;
      float: left;
      height: 100%;
      &.has-mega-menu {
        position: inherit;
      }
      &:hover > a:after,
      & > a.active:after {
        transform: scaleX(1);
        transform-origin: left;
      }
      &:hover > .mega-menu,
      &:hover > ul {
        opacity: 1;
        visibility: visible;
        pointer-events: auto;
      }
      a {
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        position: relative;
        height: 100%;
        padding: 1rem 1.2rem;
        color: white;
        font-size: 1.2rem;
        text-transform: uppercase;
        letter-spacing: 0.1em;
        backface-visibility: hidden;
        &:hover {
          text-decoration: none;
        }
      }
      > a:after {
        content: "";
        display: block;
        position: relative;
        bottom: 0;
        left: 0;
        height: 2px;
        width: 100%;
        background-color: currentColor;
        transform-origin: right;
        transform: scaleX(0);
        transition: transform 0.3s ease;
        backface-visibility: hidden;
      }
      div.mega-menu {
        opacity: 0;
        visibility: hidden;
        pointer-events: auto;
        position: absolute;
        top: 100%;
        left: 0;
        right: 0;
        margin-right: -15px;
        margin-left: -15px;
        border-top: 1px solid rgba(255, 255, 255, 0.1);
        border-bottom: 5px solid white;
        padding: 30px 50px 30px;
        background-color: #111;
        box-shadow: 0 10px 30px 0 rgba(0, 0, 0, 0.22);
        transition: all 0.3s ease;
        h6.col-title {
          color: #fff;
          text-transform: uppercase;
          font-size: 1.6rem;
          margin-bottom: 2rem;
        }
      }
      > ul {
        position: absolute;
        width: 200px;
        left: 0;
        background-color: #111;
        border-top: 1px solid rgba(255, 255, 255, 0.1);
        visibility: hidden;
        opacity: 0;
        pointer-events: none;
        transition: all 0.3s ease;
      }
      ul {
        li {
          &:first-child {
            border-top: 1px solid rgba(255, 255, 255, 0.1);
          }
          display: block;
          border-bottom: 1px solid rgba(255, 255, 255, 0.1);
          backface-visibility: hidden;
          a {
            display: block;
            color: rgba(255, 255, 255, 0.7);
            padding: 0.8rem 1.8rem;
            transition: all 0.3s ease;
            &:hover {
              color: rgba(255, 255, 255, 1);
              background-color: #000;
              text-indent: 5px;
            }
            &.new:after {
              content: "NEW";
              display: inline-block;
              background-color: red;
              color: white;
              border-radius: 3px;
              margin-left: 12px;
              font-size: 11px;
              font-weight: 700;
              padding: 1px 4px;
              letter-spacing: 0;
              text-indent: 0;
            }
          }
        }
      }
      &:last-child > ul,
      &:nth-last-child(2) > ul {
        left: auto;
        right: 0;
      }
    }
  }
}
</style>