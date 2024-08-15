# Diamagração Iphone

Desafio DIO Modelando o iPhone com UML: Funções de Músicas, Chamadas e Internet

Utilizando Lógica de programação e POO;  Conhecimentos básicos(Java);  Computador com SO Windows;  IDE Visual Studio Code

Para representar os papéis do iPhone como Reprodutor Musical, Aparelho Telefônico e Navegador na Internet em UML e posteriormente em código Java, podemos criar um diagrama de classes e interfaces que descrevem como cada papel será modelado.

Diagrama de Classes UML

1. Interface ReprodutorMusical
# Métodos:
void reproduzirMusica(String musica) 

void pausarMusica() 

void pararMusica()


2. Interface AparelhoTelefonico
# Métodos:
void fazerChamada(String numero) 

void atenderChamada() 

void encerrarChamada() 


3. Interface NavegadorInternet
# Métodos:
void abrirPagina(String url) 

void fecharPagina()

void atualizarPagina()

4. Classe Iphone

Implementa as interfaces # ReprodutorMusical, AparelhoTelefonico, e NavegadorInternet.

# Métodos:
Implementação dos métodos das interfaces.

# Explicação

1. Interfaces: Definem o contrato para os comportamentos específicos de cada papel (Reprodutor Musical, Aparelho Telefônico, Navegador na Internet).
2. Classe Iphone: Implementa todas as interfaces e fornece a implementação específica para os métodos declarados nas interfaces.


Com essa estrutura, a classe Iphone é capaz de assumir os três papéis distintos ao implementar as interfaces correspondentes.
