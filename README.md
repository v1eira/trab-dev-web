# Trabalho de Desenvolvimento Web (+ Projeto de Sistemas)
Repositório para atividades relativas ao projeto da disciplina de Desenvolvimento Web

# Objetivo
Criação de um aplicativo mobile para agendamento de horários com barbeiros, visando eliminar o tempo de espera para ser atentido por esses profissionais.

# Grupo:
David Vilaça (vilacapdavid@gmail.com) <br>
Douglas Inácio (douglasbravimbraga@hotmail.com) <br>
Ewerson Vieira (ewersonv@gmail.com) <br>
Luiz Henrique (luiz.lk.lima@gmail.com) <br>
Magno Macedo (magnomacedodeoliveira@gmail.com) <br>

# PMC
![PMC](arquivos/PMC.png)

# Minimundo

# Requisitos Não Funcionais + Táticas

| RNF | Detalhamento | Tática |
|---|---|---|
| RNF01 | O sistema deve ser construído utilizando uma linguagem de fácil manutenção. | Implementar a solução em JavaScript. |
| RNF02 | A interface do sistema deve ser responsiva. | Utilizar bootstrap. |
| RNF03 | O sistema deve ser feito para Android e iOS. | Utilizar React Native. |
| RNF04 | O sistema deve ter um meio de exibir a localização do estabelecimento num mapa. | Utilizar geolocalização. |
| RNF05 | O sistema deve autenticar seus usuários. | Autenticar o usuário através de e-mail e senha ou login via rede social. |
| RNF06 | O sistema deve retornar a pesquisa do usuário em menos de 10 segundos. | Utilizar cache para as ações do usuário. |
| RNF07 | O sistema deve ter alta disponibilidade. | Utilizar arquitetura escalável e distribuir os servidores. |
| RNF08 | O sistema deve ter meios de resolver transações pendentes (segurança contra falhas). | Usar API externa para pagamentos. |
| RNF09 | O usuário deve ser capaz de utilizar as principais atividades do sistema em, no máximo, 2 minutos. | Utilizar heurísticas de nielsen. |
| RNF10 | O sistema deve ser modularizado. | Utilizar arquitetura MVC. |
| RNF11 | O sistema precisa estar disponível para usuários de todo o país. | Disponibilizar várias threads do mesmo serviço no mesmo servidor. |

# Protótipos das Telas

## 1. Tela de Login <br>
<p align="center">
    <img src="arquivos/login.JPG"/>
</p>

## 2. Tela Lista de Barbeiros <br>
<p align="center">
    <img src="arquivos/home.JPG"/>
</p>

## 3. Tela Cortes Agendados <br>
<p align="center">
    <img src="arquivos/agendamentos.JPG"/>
</p>

O protótipo completo pode ser visto [aqui](arquivos/Barbex.pdf).

## Diagrama de classes

![diagrama-de-classes](arquivos/diagrama_de_classes.png)