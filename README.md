# LLM-as-a-judge

## **Introduction**
Ce projet a été fait en 2ème année de Master of Science IA/Data de l'école La Plateforme à Marseille. Le projet était réalisé en groupe de 3 personnes mais les codes présentés ici sont ceux que j'ai personnellement développés.
L'objectif etait de concevoir un système RAG pour les tickets SAV ou les tickets de support du SI d'une entreprise. Les performances du RAG était ensuite évalué par un LLM-as-a-Judge.  

## **Structure du Projet**

Cleaning_tickets est un jupyter notebook qui sert à faire de la préparation de données sur les tickets.
Test_rag_pipeline est un pipeline de RAG. 
LLM_as_a_judge_final est un jupyter notebook utilisant une bibliothèque pour faire du LLM-as-a-judge.
LLM_as_a_judge_fromscratch, comme le nom l'indique, est un jupyter notebook de LLM-as-a-judge sans bibliothèque spécialisée. 
