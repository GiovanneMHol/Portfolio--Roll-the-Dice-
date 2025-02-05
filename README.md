# Roll the Dice

Este é um aplicativo simples para rolar dados com valores variáveis (de D2 até D20), permitindo realizar operações matemáticas nas rolagens de dois dados. O aplicativo inclui funcionalidades como modo escuro, exibição de histórico de rolagens e a capacidade de rolar dois dados simultaneamente.

## Funcionalidades

- **Rolagem de Dados:** Permite rolar dados de D2 até D20, com a possibilidade de rolar dois dados ao mesmo tempo.
- **Operações Matemáticas:** Realize operações (soma, subtração, multiplicação e divisão) com os resultados das rolagens de dois dados.
- **Histórico:** Exibe um histórico das rolagens, com a opção de ocultá-lo.
- **Modo Escuro:** O aplicativo possui um modo escuro para uma experiência de usuário mais confortável à noite.
- **Diferenciação de Resultados:** O aplicativo destaca os resultados baixos (rolagens de 1) e altos (rolagens máximas).

## Como Rodar o Projeto

### Pré-requisitos

- [Node.js](https://nodejs.org/) - Certifique-se de que o Node.js está instalado, caso deseje rodar um servidor local para testar o código.

### Como Usar

1. Clone este repositório:
   ```bash
   git clone https://github.com/SEU-USER/SEU-REPO.git


## Erros Conhecidos e Melhorias Futuras

- ❌ **Histórico de rolagens não está implementado corretamente.**  
  - O botão "Mostrar Histórico" ainda não armazena as rolagens corretamente. Planejo corrigir isso.  

- ❌ **Modo escuro não persiste ao recarregar a página.**  
  - Ao atualizar a página, o modo escuro volta para o padrão claro. Pretendo usar `localStorage` para salvar a preferência do usuário.  

- ❌ **Problema ao rolar dois dados e dividir um pelo outro.**  
  - Se o segundo dado rolar `0`, a divisão retorna "Indefinido", pois não há tratamento para isso. Vou corrigir isso evitando divisões por zero.  

- ✅ **Melhoria planejada:** Adicionar um botão para limpar o histórico manualmente.  
