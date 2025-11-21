

# LarAmigo

Repositório: [https://github.com/CatGaby/LarAmigo.git](https://github.com/CatGaby/LarAmigo.git)

## INTRODUÇÃO

O LarAmigo é um aplicativo mobile voltado para facilitar a adoção, doação e apoio a animais, conectando ONGs, protetores independentes e pessoas interessadas. Desenvolvido como projeto acadêmico, busca promover o bem-estar animal por meio da tecnologia.

### 1.1 Tema

Adoção, doação e apoio a animais por meio de aplicativo mobile.

### 1.2 Objetivos

#### 1.2.1 Objetivo geral

Desenvolver um aplicativo que conecte pessoas e instituições para adoção, doação e apoio a animais.

#### 1.2.2 Objetivos específicos

- Facilitar o processo de adoção de animais.
- Incentivar doações para ONGs e protetores.
- Oferecer canais de comunicação entre usuários e instituições.
- Promover voluntariado e lares temporários.

---

## 2. DESCRIÇÃO GERAL DO SISTEMA

O sistema consiste em um aplicativo mobile multiplataforma, com telas para adoção, doação, cadastro/login, contato, favoritos, chat, notícias, voluntariado e lar temporário.

### 2.1 Diagnose

Diagnóstico do problema: dificuldade de adoção, falta de recursos para ONGs, baixa visibilidade de animais disponíveis.


### 2.4 Justificativa

A tecnologia aproxima pessoas e instituições, tornando o processo de adoção e doação mais ágil, transparente e seguro.

#### 2.4.1 Justificativa do Uso dos Princípios de IHC

O projeto adota princípios de Interação Humano-Computador (IHC) para garantir usabilidade, acessibilidade e experiência positiva ao usuário.

#### 2.4.2 Usabilidade e Acessibilidade

- Interface intuitiva e responsiva.
- Suporte a leitores de tela.
- Contraste adequado e navegação facilitada.

---

## 3. MODELAGEM UML

### 3.1 Regras de Negócio

- Apenas usuários autenticados podem cadastrar pets ou realizar doações.
- Animais só podem ser marcados como adotados por ONGs/protetores.
- Usuários podem favoritar pets e entrar em contato com ONGs.

### 3.2 REQUISITOS DO SISTEMA

#### 3.2.1 Requisitos Funcionais (RF)

- RF01: Permitir cadastro/login de usuários.
- RF02: Listar animais disponíveis para adoção.
- RF03: Permitir doações financeiras.
- RF04: Gerenciar favoritos.
- RF05: Enviar mensagens via chat.

#### 3.2.2 Requisitos Não Funcionais (RNF)

- RNF01: Interface responsiva.
- RNF02: Segurança dos dados.
- RNF03: Compatibilidade Android/iOS.

## 4. AMBIENTE DE DESENVOLVIMENTO

- Node.js >= 18
- Expo CLI
- React Native
- TypeScript


### 4.1 Bibliotecas

- React Navigation
- Styled Components
- Expo Linear Gradient
- React Native PagerView

## Estrutura de Pastas

```
LarAmigo/
	LarAmigo/
		.expo/
			App.tsx
			src/
				screens/
					Home.tsx
					Adoption.tsx
					Donation.tsx
					Login.tsx
					Register.tsx
					Contact.tsx
					Favorites.tsx
					FavoriteContext.tsx
					...
```

## Funcionalidades Detalhadas

- **Home:** Carrossel de imagens, exibição de pets disponíveis, favoritos.
- **Adoção:** Listagem de animais para adoção, filtros por espécie, idade e porte.
- **Doação:** Permite doações financeiras, escolha de valores e métodos de pagamento.
- **Cadastro/Login:** Autenticação de usuários, validação de dados.
- **Contato:** Canal para comunicação com ONGs/protetores.
- **Favoritos:** Gerenciamento de pets favoritos.
- **Chat:** Comunicação entre usuários.
- **Notícias:** Informações e novidades sobre o mundo pet.
- **Voluntariado:** Cadastro para voluntários.
- **Lar Temporário:** Cadastro para oferecer lar temporário.

## Tecnologias Utilizadas

- React Native (Expo)
- TypeScript
- React Navigation
- Context API
- Styled Components
- Expo Linear Gradient
- React Native PagerView

## Testes

Para rodar os testes (se implementados):
```sh
npm test
```

## Contribuição

1. Faça um fork do projeto
2. Crie uma branch (`git checkout -b feature/nova-feature`)
3. Commit suas alterações (`git commit -m 'Adiciona nova feature'`)
4. Faça um push para a branch (`git push origin feature/nova-feature`)
5. Abra um Pull Request
				screens/
					Home.tsx
					Adoption.tsx
					Donation.tsx
					Login.tsx
					Register.tsx
					Contact.tsx
					Favorites.tsx
					FavoriteContext.tsx
					...
```

## Funcionalidades Detalhadas

- **Home:** Carrossel de imagens, exibição de pets disponíveis, favoritos.
- **Adoção:** Listagem de animais para adoção, filtros por espécie, idade e porte.
- **Doação:** Permite doações financeiras, escolha de valores e métodos de pagamento.
- **Cadastro/Login:** Autenticação de usuários, validação de dados.
- **Contato:** Canal para comunicação com ONGs/protetores.
- **Favoritos:** Gerenciamento de pets favoritos.
- **Chat:** Comunicação entre usuários.
- **Notícias:** Informações e novidades sobre o mundo pet.
- **Voluntariado:** Cadastro para voluntários.
- **Lar Temporário:** Cadastro para oferecer lar temporário.

- React Navigation
- Styled Components
- Expo Linear Gradient
- React Native PagerView

### 4.2 Funções

- Cadastro/Login de usuários
- Listagem e filtro de animais
- Gerenciamento de favoritos
- Envio de mensagens
- Processamento de doações

---

## 5. CÓDIGO FONTE

O código está disponível no repositório GitHub. As principais telas e funções estão organizadas em módulos, seguindo boas práticas de desenvolvimento mobile.

---

## 6. CONSIDERAÇÕES FINAIS

O LarAmigo contribui para a causa animal, aproximando pessoas e instituições, facilitando adoção, doação e voluntariado. O projeto pode ser expandido com novas funcionalidades e integração com sistemas de ONGs.

---

## 7. BIBLIOGRAFIA

- [Documentação React Native](https://reactnative.dev/)
- [Expo](https://docs.expo.dev/)
- [React Navigation](https://reactnavigation.org/)
- Livros e artigos sobre IHC, usabilidade e acessibilidade.