# Vagrant

Projeto de laboratório do vagrant para consolidação de conhecimento e troubleshooting

## Iniciando

Os diretório possuem somente o arquivo Vagrantfile que possui a configuração da máquina que o mesmo ira realizar o download quando executar `` vagrant up``

Quando executar o comando acima será criado um diretório `.vagrant`. Evitar realizar o commit deste diretório.

### Requisitos

Para uso e necessário a instalação do [Vagrant](https://www.vagrantup.com/downloads.html) e [Oracle Virtual Box](https://www.virtualbox.org/wiki/Downloads)



### Comando Úteis

Abaixo uma lista simples de comando que pode ajudar no laboratório

Download de um box
```
vagrant init hashicorp/precise64
```

Iniciar uma máquina virtual
```
vagrant up
```
Desligar uma máquina virtual
```
vagrant halt
```
Checar status de uma máquina virtual
```
vagrant status
```
Reiniciar uma máquina virtual
```
vagrant reload
```
Desturir uma máquina virtual (Arquivos da máquina virtual ficam salvos no computador quando executar o vagrant up)
```
vagrant reload
```