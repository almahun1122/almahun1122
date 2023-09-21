gg-adidas {
    position: relative;
    box-sizing: border-box;
    display: block;
    width: 23px;
    height: 15px;
    transform: scale(var(--ggs,1));
    overflow: hidden
}
.gg-adidas::before {
    content: "";
    position: absolute;
    box-sizing: border-box;
    display: block;
    width: 5px;
    height: 18px;
    background: currentColor;
    transform: rotate(-30deg);
    left: 4px;
    bottom: -14px;
    box-shadow: 7px -2px,14px -4px
}
