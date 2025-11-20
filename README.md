# # ⏳ C.H.T - Contador de Horas Trabalhadas

O **C.H.T (Contador de Horas Trabalhadas)** é um aplicativo simples, funcional e responsivo desenvolvido com **HTML, CSS e JavaScript**, permitindo controlar e registrar facilmente sua jornada diária de trabalho.

Com ele, é possível registrar:

* Horário de **entrada**
* **Saída para almoço**
* **Retorno do almoço**
* **Saída final**
* Registrar **dias de folga**
* Acompanhar o total de horas trabalhadas

Todas as informações são salvas no navegador, garantindo que os dados permaneçam mesmo após atualizar ou fechar a página.

---

## 🔥 Funcionalidades

* Registro completo da jornada diária.
* Tela responsiva, funcionando em PC e celular.
* Botões para registrar horários com um clique.
* Armazena os dados localmente (sem servidor).
* Exportação dos registros:

  * **Excel**
  * **PDF**
  * **Impressão direta**
* Possibilidade de adicionar múltiplos dias de trabalho.

---

## 🛠️ Tecnologias Utilizadas

* **HTML5**
* **CSS3**
* **JavaScript Puro (Vanilla JS)**

---

## 📦 Instalação

1. Baixe o projeto ou clone o repositório:

   ```
   git clone https://github.com/SEU-USUARIO/cht-contador-horas.git
   ```
2. Abra o arquivo `index.html` em qualquer navegador.
3. Não precisa instalar nada – funciona 100% offline.

---

## 📁 Estrutura do Projeto

```
📦 CHT
├── index.html
├── style.css
└── app.js
```

---

## 📷 Demonstração

(Adicione aqui um print ou GIF do app funcionando)

---

## 🚀 Melhorias Futuras

* Cadastro de usuário
* Backup em nuvem
* Tema claro/escuro
* Dashboard com gráficos

---

## 📄 Licença

Este projeto é de código aberto e pode ser usado livremente.

---

## 👤 Autor

Desenvolvido por **Daniel Ferreira de Almeida Silva**.
Chronos — C.H.T (Contador de Horas Trabalhadas)

**Versão:** 1.0

## Descrição

Chronos — C.H.T é uma aplicação web simples e responsiva para controle das horas trabalhadas. Desenvolvida com HTML, CSS e JavaScript, permite ao usuário registrar dias, marcar folgas, registrar horários (entrada, início do almoço, fim do almoço, saída), salvar os dados localmente no navegador e exportar relatórios em JSON, Excel e PDF.

O objetivo do Chronos é oferecer uma ferramenta leve, sem necessidade de servidor, para profissionais que precisam acompanhar suas horas de trabalho e gerar relatórios para folha de ponto ou prestação de contas.

---

## Principais funcionalidades

* Adicionar/editar dias de trabalho.
* Registrar horários: **Entrada**, **Início do almoço**, **Fim do almoço**, **Saída**.
* Calcular automaticamente horas trabalhadas no dia e horas acumuladas no período.
* Marcar dias como **folga** ou **férias**.
* Salvar os dados localmente (LocalStorage) — permanecem após atualizar a página.
* Exportar/baixar arquivo **JSON** com todos os registros.
* Exportar relatório em **Excel (XLSX)**.
* Gerar **PDF** para impressão e download.
* Imprimir relatório direto da interface.
* Tema responsivo e compatível com celulares (design mobile-first).

---

## Tecnologias

* HTML5
* CSS3 (Responsivo)
* JavaScript (Vanilla)
* LocalStorage para persistência local
* Biblioteca opcional para exportar Excel (ex.: SheetJS) — pode ser incluída via CDN
* Biblioteca opcional para gerar PDF (ex.: jsPDF) — pode ser incluída via CDN

---

## Estrutura de arquivos (sugestão)

```
chronos-cht/
├─ index.html
├─ styles.css
├─ app.js
├─ assets/
│  ├─ logo.png
│  └─ icons/
├─ README.md
└─ examples/
   └─ sample-data.json
```

## Guia rápido de uso

* **Adicionar dia:** clique em "Adicionar dia" (ou botão +) e informe a data.
* **Registrar horários:** dentro do dia, preencha os campos de entrada, almoço e saída. O sistema calcula automaticamente a jornada e subtrai o intervalo de almoço.
* **Marcar folga:** marque a opção "Folga" para excluir a contagem de horas naquele dia.
* **Salvar:** os dados são salvos automaticamente no LocalStorage, mas há opção de "Salvar como JSON" para backup manual.
* **Exportar:** use os botões "Exportar JSON", "Exportar Excel" ou "Gerar PDF".
* **Imprimir:** botão "Imprimir relatório" formata a página para impressão.

---

## Exemplos de formato de exportação (JSON)

```json
{
  "periodo": "2025-11",
  "registros": [
    {
      "data": "2025-11-01",
      "entrada": "08:30",
      "inicio_almoco": "12:00",
      "fim_almoco": "13:00",
      "saida": "17:30",
      "horas_trabalhadas": "8:00",
      "tipo": "trabalho"
    }
  ]
}
```

---

## Boas práticas e notas

* Faça backups regulares (exportando JSON) se você depende dos dados para fins legais ou contábeis.
* Teste exportações (Excel/PDF) em casos reais para garantir formatação correta.
* A precisão do cálculo depende de horários inseridos corretamente — o app não altera fusos horários.

---

## Personalização / Recursos avançados (opcionais)

* Integração com Google Drive/OneDrive para backup na nuvem.
* Autenticação simples/local (para multiusuários) — exigiria backend.
* Relatórios por período (semana, mês, ano) com gráficos de horas.
* Exportar para formatos específicos de folha de pagamento.
* Exportar CSV além de XLSX.

---

## Roteiro para vídeo curto (30–60s)

1. Apresente o app: "Este é o Chronos — Contador de Horas Trabalhadas".
2. Mostre como adicionar um dia e registrar horários.
3. Exporte o JSON/Excel rapidamente.
4. Finalize: "Leve, offline e pronto para uso".

---

## Contribuição

Contribuições são bem-vindas! Sugestões de melhoria, correções de bugs ou novas funcionalidades podem ser enviadas via Pull Request.

1. Fork do repositório
2. Crie uma branch: `feature/nome-da-funcao`
3. Faça commit das alterações
4. Abra um Pull Request descrevendo a mudança

---

## Licença

Escolha a licença que preferir, por exemplo MIT:

```
MIT License

Copyright (c) 2025 <Daniel Fealsi>

Permission is hereby granted, free of charge, to any person obtaining a copy
... (adicione o texto completo da licença MIT se desejar)
```

---

## Contato

Se quiser, me envie sugestões e dúvidas pelo repositório ou pelo e-mail: `danielferreira19402@gmail.com`.

---

## Histórico de versões

* **1.0 (2025-11-20)** — Versão inicial com recursos básicos: registro de dias, cálculo de horas, exportação JSON/Excel/PDF e persistência local.

---

