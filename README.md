# sagu_webscraping

Scripts de web scraping de serviços para o aluno da UNEMAT

## Começando

Essas instruções ensinarão como você pode clonar esse repositório e usar os scripts em seu computador

## Instalação

### Pré requisitos

```
python3
python3-pip
git
```

Instale-os usando:

```
# Debian, Ubuntu etc
$ sudo apt-get install python3 python3-pip git
# Fedora
$ sudo dnf install python3 python3-pip git
# Arch
$ sudo pacman -S python3 python3-pip git
```

#### geckodriver

Baixa o arquivo que corresponde ao seu sistema operacional em https://github.com/mozilla/geckodriver/releases. Descomprima e adicione o geckodriver ao path. Em sistemas Linux, como Ubuntu e Fedora isso pode ser feito com:

```
# O comando abaixo cria um link para uma pasta que está no PATH. Substitua o caminho da pasta pelo seu caso

$ sudo ln -s /onde_vc_baixou/geckodriver-v0.26.0-linux64/geckodriver /usr/bin

```

### Uso

```
$ git clone https://github.com/LucasMazei/sagu_webscraping
$ pip3 install -r requirements.txt --user
```

Abra e execute os scrip:

```
$ cd sagu_webscraping
$ jupyter lab
```

## Autor:

###Lucas Mateus Mazei Sobrinho
https://lnk.bio/oPiD
