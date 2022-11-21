# goit-markup-hw-05
.menu-link::after {
  content: '';

  position: absolute;
  left: 0;
  bottom: 0;

  display: block;
  width: 100%;
  height: 5px;
  background-color: red;

  opacity: 0;
  transform: scaleX(0);
  transition: transform 250ms cubic-bezier(0.4, 0, 0.2, 1),
    opacity 250ms cubic-bezier(0.4, 0, 0.2, 1);
}

.menu-link:hover::after {
  opacity: 1;
  transform: scaleX(1);
}

.site-nav .link.current::after {
    content: "";
    position: absolute;
    left: 0;
    bottom: -1px;
    
    display: block;
    width: 100%;
    height: 4px;
    background-color: currentColor;
    border-radius: 2px;
    transition: 250ms cubic-bezier(0.4, 0, 0.2, 1);