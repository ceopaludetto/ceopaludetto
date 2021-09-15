# Opa, sou o Carlos Eduardo aka Cadú 🇧🇷

Sou estudante de ciência da computação e trabalho com desenvolvimento de software, particularmente amo Typescript, mas não vou me incomodar ~~tanto~~ em programar num projeto que contenha javascript puro. Bom, aqui você vai encontrar uns códigos que crio nas horas vagas e alguns testes/aulas feitos no passado. E logo abaixo tem o módulo em NestJS que me define. Aproveite!

```ts
@Module({
  imports: [
    TypescriptModule,
    ReactModule,
    GraphQLModule,
    CoffeModule,
    GamesModule,
    NotFunnyJokesModule,
  ],
  providers: [KnowledgeResolver, KnowledgeService],
})
export class CaduModule implements OnModuleInit {
  public constructor(private readonly logger: Logger) {}

  public onModuleInit() {
    this.logger.info("Welcome to my README.md");
  }
}
```

## Meus Links

[<img align="left" alt="ceopaludetto | LinkedIn" width="22px" src="https://image.flaticon.com/icons/png/512/174/174857.png" />][linkedin]

[<img align="left" alt="ceopaludetto | Twitter" width="22px" src="https://image.flaticon.com/icons/png/512/733/733579.png" />][twitter]

[twitter]: https://twitter.com/soreduard
[linkedin]: https://linkedin.com/in/ceopaludetto/

<br/>

## Métricas

<br/>

![Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=ceopaludetto&layout=compact&theme=dracula&custom_title=Linguagens%20Mais%20Usadas)

<br/>

![Stats](https://github-readme-stats.vercel.app/api?username=ceopaludetto&show_icons=true&count_private=true&theme=dracula&include_all_commits=true&custom_title=Minhas%20Estatísticas&locale=pt-br)
