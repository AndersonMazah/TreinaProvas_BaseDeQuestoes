# 📚 Banco de Questões - TreinaProvas

Este repositório contém arquivos **XML** que armazenam o banco de questões utilizado no projeto [TreinaProvas](https://www.treinaprovas.com.br).

Os arquivos são organizados por matéria e seguem o formato padrão de backup do sistema, permitindo a fácil importação e atualização das questões no aplicativo.

## 📂 Estrutura dos Arquivos

Cada arquivo XML contém:
- Matérias cadastradas
- Aulas vinculadas às matérias
- Questões associadas às aulas
- Alternativas de respostas para cada questão
- Justificativas pedagógicas explicando as respostas corretas

O formato segue a estrutura abaixo:
```xml
<backup>
  <materia id="UUID" nome="Nome da Matéria">
    <aula id="UUID" idmateria="UUID" nome="Nome da Aula">
      <questao id="UUID" idaula="UUID" enunciado="Texto da questão" justificativa="Justificativa da resposta correta">
        <opcao id="UUID" idquestao="UUID" correta="true|false" texto="Texto da opção"/>
      </questao>
    </aula>
  </materia>
</backup>
```

## 🚀 Como Usar

1. Faça o download do(s) arquivo(s) XML desejado(s).
2. Acesse o menu **"Cadastro > Backup e Restauração"** no TreinaProvas.
3. Importe o arquivo XML para carregar o conteúdo no aplicativo.

## 📑 Sobre o Projeto TreinaProvas

O [TreinaProvas](https://www.treinaprovas.com.br) é uma plataforma gratuita, desenvolvida em HTML, CSS e JavaScript puro, com o objetivo de ajudar estudantes a se prepararem para provas, simulados e concursos, utilizando a prática de questões e a autoavaliação.

## 🤝 Contribuições

No momento, o repositório é mantido de forma centralizada. Caso deseje sugerir correções ou melhorias nos arquivos de questões, entre em contato.

---

**Notas:**
- Os XMLs deste repositório podem ser utilizados livremente no sistema TreinaProvas.
- A estrutura dos arquivos deve ser preservada para garantir compatibilidade.

---

Feito com ❤️ por AndersonMazah
