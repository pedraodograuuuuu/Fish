#!/usr/bin/env fish

function mostrar_menu
    clear
    echo "=== MENU DE OPÇÕES ==="
    echo "1 - Farma Money"
    echo "2 - ESP Jogadores"
    echo "3 - Teleporta nas Ilhas"
    echo "4 - Shop"
    echo "0 - Sair"
    echo ""
    read -p "Escolha uma opção: " opcao

    switch $opcao
        case 1
            echo "Ativando o farm de money..."
            # Aqui você colocaria o comando real que farma dinheiro
        case 2
            echo "Ativando ESP jogadores..."
            # Aqui o comando para ativar o ESP
        case 3
            echo "Teleportando para ilha..."
            echo "Escolha a ilha:"
            echo "1 - Ilha da Caveira"
            echo "2 - Ilha do Vulcão"
            read ilha
            switch $ilha
                case 1
                    echo "Teleportando para Ilha da Caveira..."
                case 2
                    echo "Teleportando para Ilha do Vulcão..."
                case '*'
                    echo "Ilha inválida."
