\documentclass[11pt,a4paper,sans]{moderncv}       

% Definir o estilo e a cor
\moderncvstyle{casual}                             
\moderncvcolor{blue}                               

% Pacote para caracteres especiais
\usepackage[T1]{fontenc}  % Mantém para PDFLaTeX ou XeLaTeX

% Definir a largura das margens
\usepackage[scale=0.8]{geometry}

% Pacote para links
\usepackage{hyperref}

% Definir a fonte
\renewcommand{\familydefault}{\sfdefault}

% Início do documento
\begin{document}

% Cabeçalho
\name{João}{Silva}
\address{Rua Exemplo, 123}{Bairro, Cidade, RS, CEP 12345-678}
\phone[mobile]{(11) 98765-4321}
\email{joaosilva@email.com}
\social[linkedin]{joaosilva}
\social[github]{joaosilva}
\photo[64pt][0.4pt]{picture.jpg}  % Foto opcional, coloque a imagem no mesmo diretório

% Título do currículo
\begin{center}
    \textbf{\Huge Currículo Profissional}
\end{center}

\section*{Objetivo}
Formando do curso Técnico em Desenvolvimento de Sistemas do SENAC, com experiência prática em desenvolvimento de software, administração de banco de dados e análise de sistemas. Buscando uma oportunidade para aplicar meus conhecimentos e habilidades em um ambiente dinâmico e inovador.

\section*{Formação Acadêmica}
\cventry{2025}{Técnico em Desenvolvimento de Sistemas}{SENAC}{São Leopoldo, RS}{\textit{Conclusão: Dezembro 2025}}{}
\cventry{2023}{Ensino Médio}{Escola Estadual Exemplo}{São Leopoldo, SP}{\textit{Conclusão: Dezembro 2023}}{}

\section*{Experiência Profissional}
\subsection*{Estagiário de Desenvolvimento de Sistemas}
\cventry{2025}{Jan/2025 - Dez/2025}{Empresa Exemplo}{São Leopoldo, RS}{\textit{Desenvolvimento de software e administração de banco de dados}}{%
Desenvolvimento de aplicações em Java e Python, manutenção de sistemas internos, criação de novos módulos de software, modelagem de banco de dados MySQL. Trabalhei com metodologias ágeis (Scrum) e participei de testes de qualidade.}

\subsection*{Freelancer - Desenvolvedor Web}
\cventry{2024}{Jul/2024 - Dez/2024}{Autônomo}{São Leopoldo, RS}{\textit{Desenvolvimento de sites responsivos}}{%
Criação de sites para pequenas empresas utilizando HTML, CSS, JavaScript e integração com banco de dados MySQL. Desenvolvimento de sistemas de e-commerce simples.}

\subsection*{Estagiário de Suporte Técnico}
\cventry{2023}{Jun/2023 - Dez/2023}{Empresa Exemplo}{São Leopoldo, RS}{\textit{Suporte técnico e manutenção de sistemas}}{%
Atuação no suporte a usuários internos e externos, instalação de software e configuração de redes, além de manutenção de sistemas de TI.}

\section*{Habilidades Técnicas}
\begin{itemize}
    \item \textbf{Linguagens de Programação:} Java, Python, HTML, CSS, JavaScript, SQL
    \item \textbf{Frameworks e Ferramentas:} Angular, React, Spring Boot, Git, Docker, Visual Studio Code, IntelliJ IDEA
    \item \textbf{Bancos de Dados:} MySQL, PostgreSQL
    \item \textbf{Metodologias Ágeis:} Scrum, Kanban
    \item \textbf{Sistemas Operacionais:} Windows, Linux
\end{itemize}

\section*{Cursos Complementares}

\cventry{2024}{Curso de Banco de Dados MySQL}{Coursera}{Online}{\textit{Aprofundamento em modelagem e administração de banco de dados MySQL}}{}
\cventry{2025}{Certificação AWS - Cloud Practitioner}{AWS}{Online}{\textit{Fundamentos de computação em nuvem com AWS}}{}

\section*{Projetos Acadêmicos}
\subsection*{Sistema de Gestão de Biblioteca}
\cvitem{Descrição}{Desenvolvimento de um sistema de gerenciamento de livros e empréstimos, utilizando Java e MySQL. A aplicação segue a arquitetura MVC e possui interface gráfica.}

\subsection*{Aplicativo de Controle Financeiro Pessoal}
\cvitem{Descrição}{Criação de um aplicativo mobile usando React Native para controle de despesas pessoais, com integração ao banco de dados Firebase para armazenamento seguro de dados.}

\section*{Idiomas}
\begin{itemize}
    \item \textbf{Português:} Nativo
    \item \textbf{Inglês:} Intermediário (Leitura, escrita e conversação)
\end{itemize}

\section*{Informações Adicionais}
\begin{itemize}
    \item Disponibilidade para início imediato.
    \item Interesse em atuar nas áreas de desenvolvimento de software e administração de sistemas.
\end{itemize}

\end{document}
