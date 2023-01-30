# Opa, sou o Carlos Eduardo aka Cadú(ele/dele) 🇧🇷

Sou estudante de ciência da computação e trabalho com desenvolvimento de software, particularmente amo Typescript, mas não vou me incomodar em programar num projeto que contenha Javascript puro. Bom, aqui você vai encontrar uns códigos que crio nas horas vagas e alguns testes/aulas feitos no passado. E logo abaixo tem o módulo em NestJS que me define.

```ts
@Module({
  imports: [
    TypescriptModule,
    ReactModule,
    GraphQLModule,
    CoffeModule,
    GamesModule,
  ],
  providers: [KnowledgeResolver, KnowledgeService, BoringJokesService],
  exports: [BoringJokesService],
})
export class CaduModule implements OnModuleInit {
  public constructor(private readonly logger: Logger) {}

  public onModuleInit() {
    this.logger.info("Welcome to my README.md");
  }
}
```

<div align="center">
  <a href="mailto:ceo.paludetto@gmail.com"><img src="https://img.shields.io/badge/-Gmail-%23EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail"></a>
  <a href="https://www.linkedin.com/in/ceopaludetto" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="https://twitter.com/ceopaludetto" target="_blank"><img src="https://img.shields.io/badge/-Twitter-%231DA1F2?style=for-the-badge&logo=twitter&logoColor=white" alt="Twitter"/></a>
</div>

##

<div align="center">
  <img height="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg" alt="Typescript"/>
  <img height="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="Javascript"/>
  <img height="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg" alt="HTML"/>
  <img height="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg" alt="CSS"/>
  <img height="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original.svg" alt="ReactJS"/>
  <img height="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/svelte/svelte-original.svg" alt="Svelte"/>
  <img height="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nestjs/nestjs-plain.svg" alt="NestJS"/>
  <img height="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/graphql/graphql-plain.svg" alt="GraphQL"/>
  <img height="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original.svg" alt="PostgreSQL"/>
  <img height="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original.svg" alt="MongoDB"/>
  <img height="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/git/git-plain.svg" alt="Git"/>
  <img height="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/swift/swift-original.svg" alt="Swift"/>
</div>
