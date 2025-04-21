# Curso de Git Embarcatech

Configurando git localmente:

```bash
git config --global user.name "buguno"
git config --global user.email "brunnodesouzabezerra@gmail.com"
```

Criando e acessando o diretorio para o repositório:

```bash
mkdir curso-git-embarcatech && cd curso-git-embarcatech
```

Criando arquivo com as informacoes do aluno:

```bash
echo "# Infos\n\nNome: Bruno de Souza Bezerra\nMatricula: 20251ZL00130059" >> infos.md
```

Iniciando repositório git localmente:

```bash
git init
```

Adicionando arquivo em staging:

```bash
git add infos.md
```

Adicionando mensagem de commit ao arquivo `info.md`.

```bash
git commit -m "docs(infos): creating file and adding author infos"
```

Criando a branch principal

```bash
git branch -M master
```

Adicionando repositório remoto ao local:

```bash
git remote add origin https://github.com/buguno/curso-git-embarcatech.git
```

Fazendo envio do commit para o repositório remoto:

```bash
git push -u origin master
```
