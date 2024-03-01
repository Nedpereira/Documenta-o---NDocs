# Guia de Renderização Condicional no React/React Native
 > Este guia aborda como utilizar lógicas condicionais para a renderização de componentes no React e no React Native. A renderização condicional é um padrão comum para exibir componentes ou elementos baseados em certas condições.

- Sumário
- Introdução
- Operador Ternário
- Usando if para Lógicas Complexas
- Boas Práticas

### Introdução
Renderizar componentes de forma condicional permite que você mostre ou esconda partes da sua aplicação baseado em determinados critérios, como o estado da aplicação, props ou qualquer outra lógica.

**Operador Ternário**

O operador ternário é uma maneira concisa de realizar uma operação if-else. É especialmente útil para escolhas simples e pode ser diretamente incorporado no JSX.

**Sintaxe Básica:**

`{condicao ? <ComponenteSeVerdadeiro /> : <ComponenteSeFalso />}`

**Exemplo Prático:**

```
const MeuComponente = ({ isLoading }) => (
  <div>
    {isLoading ? <LoadingComponent /> : <MainContent />}
  </div>
);
```

**Usando if para Lógicas Complexas**

Para componentes maiores ou quando a condição é mais complexa, é preferível usar uma declaração if fora do retorno do componente.

**Exemplo com Componente Complexo:**

```
const MeuComponente = ({ isLoading }) => {
  if (isLoading) {
    return (
      <div className="loading-container">
        <p>Carregando...</p>
        <img src="loading.gif" alt="Carregando" />
      </div>
    );
  } else {
    return (
      <div className="content">
        <h1>Título do Conteúdo</h1>
        <p>Este é o conteúdo principal.</p>
        <img src="content-image.jpg" alt="Conteúdo" />
      </div>
    );
  }
};
```

**Boas Práticas**

- Mantenha a Simplicidade: Evite complicar a lógica condicional. Se necessário, divida em componentes menores.
- Evite Lógicas Complexas no JSX: Mantenha o código limpo fazendo as verificações antes do retorno.
- Short-Circuit para Renderização Condicional: Quando aplicável, use o operador && para uma condição que só precisa renderizar algo se verdadeiro.
- Componentes Menores: Para componentes grandes, considere dividir em componentes menores para melhorar a reutilização e a legibilidade do código.
- Testes: Assegure-se de testar todas as condições possíveis para garantir que a UI se comporte como esperado.
