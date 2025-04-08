% Definção da classe do documento
\documentclass[a4paper, 12pt]{article}
% Definir que o documento será do tipo 'article', com papel A4 e fonte tamanho 12pt
\usepackage[utf8]{inputenc}
% Define a codificação do texto como UTF-8 para garantir a correta exibição dos caracteres especiais
\usepackage{geometry} 
% Pacote para personalizar as margens da página
\geometry{top=2.5cm, bottom=2.5cm, left=2.5cm, right=2.5cm}
% Define as margens de 2,5 para todos os lados da página

\title{currículo}
% Define o título do documento como "currículo"
\author{João Silva}
% Define o nome do candidato
\begin{document} % Início do conteúdo do documento
% Geração do título do currículo 
\maketitle % Comando que insere o título  (Currículo)
% Informações do candidato (sem identação na primeira linha)
\noindent \textbf{Nome:} João da Silva \\ % Exibe o nome em negrito 
\textbf{Endereço:} Rua dos códigos, 123 - Bairro: VSCode - Cidade: Windows % Exibe o endereço
\textbf{Telefone:}(51)99999-9999 \\ % Exibe o telefone 
\textbf{E-mail:} joao.silva@email.com \\ % Exibe o e-mail
\textbf{LinkedIn:}linkedin.com/in.joaodasilva \\ % Exibe o LinkedIn
\textbf{GitHub:}github.com/joaodasilva % Exibe o GitHub 

\vspace{1cm} % Cria um espaço vertical de 1 cm entre as seções

% Início da seção "Objetivo"
\section*{Objetivo} % Cria uma seção não numerada com o título "Objetivo"
Busco oportunidade de estágio ou emprego como Desenvolvedor de Sistemas, onde possa aplicar meus conhecimentos e crescer profissionalmente.

\vspace{0.5cm} % Cria um espaço vertical de 1 cm entre as seções

% Início da seção "Formação Acadêmica"
\section*{Formação Acadêmica} % Cria uma seção não numerada com o título "Formação Acadêmica"
\noindent \textbf{Técnico em Desenvolvimento de Sistemas} \\ % Exibe o título do curso em negrito
SENAC São Leopoldo, RS \\ % Nome da instituição
\textbf{Situação: }  em andamento (Conclusão 2026) % data de conclusão do curso

% Início da seção "Experiência Profissional"
\section*{Experiência Profissional} % Cria uma seção não numerada com o título "Experiência Profissional"
\noindent \textbf{Estagiário em Desenvolvimento de Sistemas }
Empresa XYZ - São Leopoldo, RS \\
Janeiro DE 2024 - Atualmente \\
\begin{itemize}
    \item Desenvolvimento e manutenção de sistemas web utilizando HTML, CSS, Javascript.
    \item Criação de bancos de dados MySQL e integração com sistemas.
    \item Suporte técnico e auxílio na gestão de projetos.
\end{itemize}
\vspace{0.5cm} 
% Início da seção " Habilidades "
\section*{Habilidades}
\begin{itemize}
    \item Linguagens de programação: Java, JavaScript, Python, TypeScript, C.
    \item  Desenvolvimento web: HTML5, CSS3, JavaScript, Bootstrap.
    \item  Banco de Dados: MySQL, SQL Server.
    \item  Ferramentas: Git, Visual Studio Code, NetBeans, Eclipse.
    \item  Sistema Operacional: Windows e Linux.
\end{itemize}
\vspace{0.5cm}
% Início da seção "Certificado"
\section*{Certificados} 
\begin{itemize}
    \item \textbf{Certificação em Desenvolvimento Web} - SENAC São Leopoldo, 2025 
    \item  \textbf{Certificação em Banco de Dados MySQL} - SENAC São Leopoldo, 2025
\end{itemize}

\end{document}
