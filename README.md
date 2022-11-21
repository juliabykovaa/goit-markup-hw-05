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

    <li class="flex-item">
                        <div class="flex-thumb">
                        <a href="" class="flex-link link">
                            <img class="image" src="./images/project-3.jpg" alt="ресторан" width="370">
                        </div>
                            <div class="project-names">
                                <h3 class="title">Ресторан Seafood</h3>
                                <p class="title-description">Додаток</p>
                            </div>
                            <div class="flex-overlay">
                                <p>Ресурс пропонує комплексні пропозиції з різним рівнем функціоналу та сервісів. Все це дозволить відвідувачу отримати
                                вичерпні відомості про компанію чи приватну особу.</p>

                            </div>
                        </a>

<div class="flex-thumb">
        <img class="image" src="./images/project-3.jpg" alt="ресторан" width="370">

        <div class="flex-overlay">
          <p></p>
        </div>
    </div>

      <div class="project-names">
                <h3 class="title">Ресторан Seafood</h3>
                                <p class="title-description">Додаток</p></a>
                            </div>
  </body>
</html>

<a href="" class="flex-link link">
                            <div class="flex-thumb">
                                <img class="image" src="./images/project-1.jpg" alt="Технокряк" width="370">
                                    <div class="flex-overlay">
                                        <p class="text-overlay">Ресурс пропонує комплексні пропозиції з різним рівнем функціоналу та сервісів. Все це дозволить відвідувачу отримати
                                вичерпні відомості про компанію чи приватну особу.</p>
                                    </div>
                            </div>
                            <div class="project-names">
                                <h3 class="title">Технокряк</h3>
                                <p class="title-description">Dt</p></a>
                                </div>
                            </a>