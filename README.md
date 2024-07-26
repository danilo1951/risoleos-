# risoleos-
.cabeçalho_menu-hamburguer {
    width: 24px;
    height: 24px;
    background-image: url("../img/Menu.svg");
    display: inline-block;
}

.cabeçalho {
    background-color: var(--branco);
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.container {
    display: flex;
    align-items: center;
}

.container__imagem {
    padding: 1em;
}



.lista-menu {
    display: none;
    
} 

.container__botão:checked~, menu{
    display: block; 
}
