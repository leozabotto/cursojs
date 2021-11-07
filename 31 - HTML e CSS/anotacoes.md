# ESTRUTURA DO HTML

## Todos os sites que vemos no navegador estão executando HTML

Extensão: .html
HTML - Hyper Text Markup Language

Foco do HTML -> Semântica / Estrutura da página

HTML é composto por TAGS.

## Tags podem ter corpo ou não

<tag atributo="valor1 valor2"> -- Tag de Anertura
  // corpo
  <tagsemcorpo />
</tag> -- Tag de fechamento

* Hierarquia das Tags
HTML é Case Insensetive
validator.w3.org -> validar documento HTML




# Meta ViewPort
Diz para o navegador que a página deverá responder à tela do dispositivo
Faz com que a janela virtual (viewport) deverá se adequar à tela física




# Atributos de ID e class
id -> identificador da tag (deve ser único na página)
class -> define uma classse para a tag (pode repetir)

boa prática -> usar - , e não camel case





# Headings
Tags para Títulos / Subtítulos
Muito importante para SEOs (mecanismos de pesquisa buscam por ela)
Vai do H1 ao H6

aria-label -> acessibilidade (para screen readers) / às vezes o texto
dentro da tag não define não bem a definição do item, então é como
se fosse uma descrição (label).