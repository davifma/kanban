```mermaid
erDiagram 
     ALUNO {
        string RGM PK
        string nome
        string sobrenome
     }
     DISCIPLINA{
        string ID_Disciplina PK
        string nome
        string descricao
     }
     CURSO{
        string RGM_Aluno FK
        string ID_Disciplina FK
     }
    CURSO }|--|| ALUNO : Faz
    CURSO }|--|| DISCIPLINA : Compoe
```
