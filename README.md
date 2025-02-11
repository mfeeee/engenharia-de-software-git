# Controle de Versões em Engenharia de Software

Este repositório contém uma demonstração prática sobre controle de versões utilizando Git e GitHub/GitLab. O objetivo é mostrar como criar um repositório, fazer commits, criar branches e abrir pull requests.

## 📌 Passos Demonstrados

### 1️⃣ Criando um Repositório
1. Acesse [GitHub](https://github.com) ou [GitLab](https://gitlab.com).
2. Clique em **New Repository**.
3. Defina um nome para o repositório e configure a visibilidade (público ou privado).
4. (Opcional) Inicialize com um **README** e escolha uma licença.
5. Clique em **Create Repository**.

### 2️⃣ Clonando o Repositório
No terminal, execute:
```sh
git clone https://github.com/SEU_USUARIO/NOME_DO_REPOSITORIO.git
cd NOME_DO_REPOSITORIO
```

### 3️⃣ Criando um Arquivo e Fazendo um Commit
Crie um arquivo `index.txt`:
```sh
echo "Primeiro commit!" > index.txt
```
Adicione e faça o commit:
```sh
git add index.txt
git commit -m "Adicionando arquivo inicial"
```

### 4️⃣ Enviando para o Repositório (Push)
```sh
git push origin main
```

### 5️⃣ Criando uma Branch
```sh
git checkout -b nova-feature
```
Faça uma alteração e adicione:
```sh
git add index.txt
git commit -m "Alteração na nova feature"
git push origin nova-feature
```

### 6️⃣ Criando um Pull Request
1. Acesse o repositório no GitHub/GitLab.
2. Vá até **Pull Requests** (GitHub) ou **Merge Requests** (GitLab).
3. Clique em **New Pull Request**.
4. Escolha a branch `nova-feature` para mesclar com `main`.
5. Adicione um título e descrição e clique em **Create Pull Request**.

---
## 📚 Referências
- [Documentação Git](https://git-scm.com/doc)
- [Guia do GitHub](https://docs.github.com/pt)
- [Guia do GitLab](https://docs.gitlab.com/ee/)

👩‍💻 *Seminário sobre Controle de Versões - Engenharia de Software*
