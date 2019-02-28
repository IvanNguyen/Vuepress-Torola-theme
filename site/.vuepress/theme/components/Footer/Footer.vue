<template>
  <footer id="footer">
    <!-- Copyright -->
    <small class="small">© Copyright. AchtungThemes 2018</small>

    <!-- Social/Contact Links -->
    <div class="small text-links">
      <a href="#">Facebook /</a>
      <a href="#">Behance /</a>
      <a href="#">Instagram</a>
    </div>
  </footer>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
#footer {
    display: flex;
    justify-content: space-between;
    align-items: center;
    position: relative;
    left: 0;
    bottom: 0;
    width: 100%;
    height: 45px;
    padding: 0 50px;
    background-color: black;
    border-color: 1px solid rgba(255,255,255,.08);
    color: #717171;
    .text-links {
        color: white;
        white-space: nowrap;
        overflow: hidden;
        text-overflow: ellipsis;
        a {
            position: relative;
            text-decoration: none;
            color: inherit;
            font-size: 1.4rem;
            &:after {
                content: '';
                height: 1px;
                width: 100%;
                background-color: currentColor;
                position: absolute;
                bottom: 0;
                left: 0;
                transform: scaleX(0);
                transform-origin: right;
                transition: transform .3s ease,-webkit-transform .3s ease;
            }
            &:hover:after {
                transform: scaleX(1);
                transform-origin: left;
            }
        }
    }

}
</style>