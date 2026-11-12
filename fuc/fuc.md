# Ficha de Unidade Curricular

## Caracterização da Unidade Curricular 

1. Designação da unidade curricular  
[4173] Linguagens e Ambientes de Execução / Languages and Managed Runtimes 

2. Sigla da área científica em que se insere  
IC

3. Duração  
Semestral
 
4. Horas de trabalho (número total de horas de trabalho)  
162

5. Horas de contacto  
Total: 60    T: 36    TP: 9     PL: 15

6. % Horas de contacto a distância  
Até 25%

7. Créditos ECTS  
6

8. Docente responsável e respetiva carga letiva na Unidade Curricular [1619]
Fernando Miguel Santos Gamboa Lopes de Carvalho, 120 horas

9. Outros docentes e respetivas cargas letivas na unidade curricular [1245] José
Luís Falcão Cascalheira, 120 horas [2108] Fernanda Gonçalves de Oliveira Passos,
60 horas

## 10. Objetivos de aprendizagem e a sua compatibilidade com o método de ensino (conhecimentos, aptidões e competências a desenvolver pelos estudantes)

Os estudantes que terminam com sucesso esta unidade curricular serão capazes de:

1. Comparar e utilizar diferentes construções comuns em linguagens de
   programação modernas (tais como Java e Kotlin), enquadrando diferentes
   paradigmas de programação, e o seu suporte no ambiente de execução.

2. Entender os principais constituintes de um ambiente de execução para
   linguagens de alto nível, e saber comparar diferentes abordagens de sistemas
   de tipos destes ambientes.

3. Usar metadados em tempo de execução (reflexão) para examinar tipos e usar
   metaprogramação para analisar e transformar programas em tempo de execução.

4. Analisar o desempenho de programas _managed_ (controlados) e usar
   eficientemente o suporte automático de gestão de memória (_garbage
   collection_).

## 10. Intended learning outcomes (knowledge, skills and competences to be developed by the students)

A student completing this course unit should be able
to:

1. Compare and use different common constructs in modern programming languages
   (such as Java and Kotlin), mapping different programming paradigms, and their
   support in the execution environment.

2. Understand the main constituents of managed runtimes, and know how to compare
   different type systems approaches in these environments.

3. Use runtime metadata (reflection) to examine types and use metaprogramming to
   analyze and transform programs at runtime.

4. Analyze the performance of managed programs and efficiently use automatic
   memory management support (garbage collection).

## 11. Conteúdos programáticos.  

I. Principais construções de linguagens suportadas em ambientes de execução para
linguagens de alto nível (managed runtimes) e a sua contextualização em
diferentes paradigmas de programação, tendo como principal caso de estudo a
máquina virtual Java.

II. Principais constituintes dos ambientes de execução _managed_, nomeadamente:
_class loader_, _verifier_, _just-in-time compiler_, metadados e gestão de memória.

III. Comparação de sistemas de tipos para ambientes de execução managed quanto
às regras de equivalência, compatibilidade e inferência.

IV. API de reflexão em Java e Kotlin, incluindo casos práticos de metaprogramação no
desenvolvimento de software.

V. Modelo de pilha e registos. Análise das principais instruções bytecode Java
apoiada em ferramentas de suporte à reflexão estrutural (e.g. ASM, Class-File
API).

VI. Introdução à análise de desempenho de programas para a JVM e uso de ferramentas de
monitorização e microbenchmarking (exemplo JMH).

VII. Introdução aos algoritmos de garbage collection na JVM .

## 11. Syllabus

I. Main constructions of languages supported in managed runtimes, and their
contextualization in different programming paradigms, using as main case study
the Java Virtual Machine (JVM).

II. Main constituents of managed runtimes, namely: class loader, verifier,
just-in-time compiler, metadata and memory management.

III. Comparison of type systems for managed runtimes regarding: equivalence
rules, compatibility and inference.

IV. Java and Kotlin reflection API and metaprogramming case studies in software
development.

V. Execution stack model and records. Analysis of the main Java bytecode
instructions supported by tools for structural reflection (e.g. ASM, Class-File
API).

VI. Introduction to the performance analysis of Java programs, and the use of
monitoring tools and microbenchamrking (e.g. JMH).

VII. Introduction to garbage collection algorithms in the JVM.


## 12. Demonstração da coerência dos conteúdos programáticos com os objetivos de aprendizagem da unidade curricular.

Esta unidade curricular identifica os principais problemas resolvidos por um
ambiente de execução para linguagens de alto nível e o suporte que fornece ao
desenvolvimento de aplicações. Em particular são analisadas diferentes
construções disponíveis nestas linguagens e nos sistemas de tipos, usando como
principal caso de estudo a linguagem Java.

A coerência entre os conteúdos programáticos e os objetivos da unidade
curricular é a seguinte:
* O objetivo 1 é alcançado através dos conteúdos I e III;
* O objetivo 2 é alcançado através dos conteúdos II, III, e IV;
* Os conteúdos IV e V contribuem para o objetivo 3; 
* Os conteúdos V, VI e VII pretendem concretizar o objetivo 4.

## 12. Evidence of the syllabus coherence with the curricular unit’s intended learning outcomes

This course unit identifies the main problems solved by an execution environment
for high-level languages and the support it provides for application
development. In particular, it analyzes different constructs available in these
languages and their type systems, using Java as the main case study.

The coherence between the program contents and the objectives of the course unit
is as follows:
* Objective 1 is achieved through contents I and III; 
* Objective 2 is achieved through contents II, III, and IV;
* Contents IV and V contribute to objective 3;
* Contents V, VI, and VII aim to achieve objective 4.

## 13. Metodologias de ensino e de aprendizagem específicas da unidade curricular articuladas com o modelo pedagógico.  

O ensino teórico-prático é planeado durante o semestre em 30 aulas que
correspondem a 60 horas de contacto, organizados em 36 horas de Ensino teórico
(T), 9 horas de Ensino teórico-prático (TP), e 15 horas de Ensino prático e
laboratorial (PL). 

As aulas Teóricas (T) destinam-se à exposição de conceitos e definições
teóricas, de modo expositivo dialogado, com momentos de análise e discussão de
temas relevantes conducentes à compreensão e reflexão crítica. Os conceitos são
desenvolvidos pelo docente, salientando o seu fundamento, o seu enquadramento
teórico e concetual, a sua vertente prática e aplicação a novas situações. O
estudante deverá questionar o docente, para esclarecimentos e explicações. Por
sua vez, o docente tem uma abordagem proactiva promovendo participação dos
estudantes para aplicação de conhecimentos já adquiridos no curso.

O Ensino teórico-prático (TP) destina-se à consolidação, utilização e aplicação
dos conceitos e definições ministrados no ensino teórico (T), através da
realização de exercícios, desafios e esclarecimento de dúvidas.

O Ensino prático e laboratorial (PL) destina-se à conceção e desenvolvimento,
por parte dos estudantes, de um projeto supervisionado pelos docentes. A
preparação teórica anterior por parte dos estudantes é fundamental. Destas
atividades resulta uma avaliação, baseada no desempenho em laboratório,
relatório da atividade e uma discussão final do trabalho desenvolvido para
validação dos conhecimentos.

## 13. Teaching and learning methodologies specific to the curricular unit articulated with the pedagogical model. 

The theoretical-practical instruction is planned over the course of the semester
across 30 classes, amounting to 60 contact hours—organized into 36 hours of
theoretical instruction (T), 9 hours of theoretical-practical instruction (TP),
and 15 hours of practical and laboratory instruction (PL).

Theoretical classrooms (T) are intended for the presentation of theoretical
concepts and definitions in a dialogued expository manner, with moments of
analysis and discussion of relevant topics leading to understanding and critical
reflection. The concepts are developed by the lecturer, highlighting their
foundation, theoretical and conceptual framework, practical aspects, and
application to new situations. Students should ask questions for clarification
and explanations. In turn, the instructor takes a proactive approach, promoting
student participation to apply knowledge already acquired in the course.  

Theoretical-practical teaching (TP) is aimed at consolidating, using, and
applying the concepts and definitions taught in theoretical classes (T) through
exercises, challenges, and clarification of doubts.  

Practical and laboratory teaching (PL) is aimed at the design and development of
a project by students, supervised by the instructors. Prior theoretical
preparation by students is essential. These activities result in an assessment
based on laboratory performance, an activity report, and a final discussion of
the work developed to validate knowledge.

## 14. Avaliação.  

A unidade curricular tem avaliação distribuída com exame final. Os resultados da
aprendizagem são avaliados individualmente através da prova escrita realizada no
final do semestre (PE) e da avaliação do trabalho prático realizado durante o
semestre (TP). Durante o acompanhamento do trabalho prático é avaliado o
desempenho individual em laboratório juntamente com uma discussão final do
trabalho prático (TP). A nota final é a média ponderada da prova escrita (PE)
(50%) e do desempenho em laboratório juntamente com a avaliação individual
obtida na discussão final do trabalho prático (TP) (50%). Cada uma das
componentes da avaliação (PE e CP) tem de ter uma classificação superior ou
igual a 9,50 valores.


## 14. Assessment. 

The course unit follows a continuous assessment model with a final exam.
Learning outcomes are assessed individually through a written exam held at the
end of the semester (PE) and through the evaluation of the practical work
carried out during the semester (TP). During the development of the practical
work, individual performance in the laboratory is assessed, together with a
final discussion of the practical work. The final grade is the weighted average
of the written exam (PE) (50%) and the practical work (TP) (50%), including
laboratory performance and the individual assessment obtained in the final
discussion. Each assessment component (PE and TP) must have a grade equal to or
higher than 9.5 (on a 0–20 scale).



## 15. Demonstração da coerência das metodologias de ensino e avaliação com os objetivos de aprendizagem da unidade curricular 

O conhecimento dos aspetos teóricos da unidade curricular é obtido por meio de
aulas teórico-práticas e de exercícios interativos. As aulas são complementadas
com sessões práticas, onde os alunos devem resolver problemas usando as
ferramentas de desenvolvimento que serão usadas na resolução de um projeto de
desenvolvimento de software.

Este projeto inclui um conjunto de desafios que devem ser resolvidos através da
aplicação do conhecimento adquirido. A avaliação do projeto é baseada em uma
discussão final que aborda as soluções desenvolvidas pelo aluno.

## 15. Evidence of the teaching methodologies coherence with the curricular unit’s intended learning outcomes 

Knowledge of the theoretical aspects of the course unit is obtained through
theoretical-practical classrooms and interactive exercises. Classrooms are
complemented with practical sessions, where students must solve problems using
the development tools that will be used in the resolution of a software
development project.

This project includes a set of challenges that must be solved by applying the
acquired knowledge. The project evaluation is based on a final discussion that
addresses the solutions developed by the student.

## 16. Bibliografia de consulta/existência obrigatória

Miguel Gamboa, The Managed Runtime Environment: Diving into the JVM with Kotlin,
First Edition, http://leanpub.com/kotlinonjvm, 2024

Benjamin Evans, Jason Clark, and Martijn Verburg, The Well-Grounded Java
Developer, Second Edition, October 2022, ISBN 9781617298875
 
## 17. Objetivos de Desenvolvimento Sustentável (ODS)

* 8 Promover o crescimento económico inclusivo e sustentável, o emprego pleno e
  produtivo e o trabalho digno para todos

* 9 - Construir infraestruturas resilientes, promover a industrialização
  inclusiva e sustentável e fomentar a inovação 

* 12 - Garantir padrões de consumo e de produção sustentáveis 

* 17 - Reforçar os meios de implementação e revitalizar a parceria global para o
  desenvolvimento sustentável 

## 17. Sustainable Development Goals

* 8 - Promote sustained, inclusive and sustainable economic growth, full and
  productive employment and decent work for all

* 9 - Build resilient infrastructure, promote inclusive and sustainable
  industrialization and foster innovation

* 12 - Ensure sustainable consumption and production patterns

* 17 - Strengthen the means of implementation and revitalize the Global
  Partnership for Sustainable Development
