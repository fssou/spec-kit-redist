# spec-kit-redist

Redistribuição do [`spec-kit`](https://github.com/github/spec-kit) do GitHub para o **PyPI**.

Este repositório existe para publicar o pacote em um formato nativo do ecossistema Python, com distribuição via `pip` e integração direta com fluxos corporativos de governança, segurança e conformidade.

## Por que esta redistribuição existe?

### Acessibilidade em ambientes restritos

Em muitas organizações, o acesso direto à organização do GitHub ou ao tráfego de saída para domínios do GitHub é bloqueado, filtrado ou fortemente controlado. Ao disponibilizar o pacote no PyPI, o consumo passa a ocorrer pelo canal padrão do Python, reduzindo barreiras de adoção para equipes que operam sob essas restrições.

### Segurança, governança e compliance

Publicar o artefato no formato padrão do ecossistema Python facilita processos de Governança de TI e análise de cadeia de suprimentos de software.

Isso permite que o componente seja submetido com facilidade a ferramentas automatizadas de SCA (Software Composition Analysis), como Snyk, Mend, Sonatype Nexus e soluções equivalentes, além de auditorias de segurança e validações internas antes da instalação.

## Instalação

Recomendamos o uso do [`uv`](https://docs.astral.sh/uv/) para isolar o pacote e o binário em um ambiente gerenciado.

```bash
uv tool install spec-kit-redist
```

Se preferir usar `pip` diretamente:

```bash
pip install spec-kit-redist
```

## Disclaimer

Este projeto é uma redistribuição do [`spec-kit`](https://github.com/github/spec-kit) original. Todos os direitos, marcas, autoria e o código-fonte original pertencem aos mantenedores do `spec-kit` do GitHub.

Este repositório não reivindica propriedade sobre o projeto upstream; ele existe apenas para ampliar a disponibilidade do pacote por meio do PyPI.
