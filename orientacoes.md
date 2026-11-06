Vamos contextualizar algumas atividades que realizamos até a etapa do projeto onde inserimos os componentes principais e nativos do react-native.

# Componentes: toda vez que o import dentro do nosso arquivo, estamos informando que estes componentes serão importados da biblioteca (fremework).
Componente é o desenvolvimento de uma parte reutilizável da interface. Um componente pode sewr nativo ou podemos criar nosso próprio componente.
## Exemplo:
### Componentes nativos:
<View>
<Text>
<Image>
<TextInput>

No nosso exercício, AppTarefas, quando criamos o arquivo nota-tarefa.tsx e dentro dele criamos uma função que irá retornar uma <View> ou <Text>, então este é o componente que estamos criando não é nativo, O arquivo nova-tarefa.tsx contém o componente chamado tarefa.

# Prop: uma prop significa uma informação que passamos para um componente. É uma propriedade. Por Exemplo, quando usamos "algo" para modificar o componente estamos inserindo uma prop.

Exemplo:

export funtion NovaTarefa({titulo: string}) {
    return (
        <View>
            <Text> {titulo} </Text>
        </View>
        )
}
Então, título é uma prop do componente NovaTarefa