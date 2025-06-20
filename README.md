<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="120" alt="Nest Logo" /></a>
</p>

## Description

[Nest](https://github.com/nestjs/nest) framework TypeScript starter repository.

## Project setup

```bash
$ npm install
```

## Compile and run the project

```bash
# development
$ npm run start

# watch mode
$ npm run start:dev

# production mode
$ npm run start:prod
```

## Run tests

```bash
# unit tests
$ npm run test

# e2e tests
$ npm run test:e2e

# test coverage
$ npm run test:cov
```

## Deployment

When you're ready to deploy your NestJS application to production, there are some key steps you can take to ensure it runs as efficiently as possible. Check out the [deployment documentation](https://docs.nestjs.com/deployment) for more information.

If you are looking for a cloud-based platform to deploy your NestJS application, check out [Mau](https://mau.nestjs.com), our official platform for deploying NestJS applications on AWS. Mau makes deployment straightforward and fast, requiring just a few simple steps:

```bash
$ npm install -g @nestjs/mau
$ mau deploy
```

With Mau, you can deploy your application in just a few clicks, allowing you to focus on building features rather than managing infrastructure.

## Project Dependencies

### Development Tools
- `@swc/cli` and `@swc/core`: Rust-based TypeScript compiler
- `@types/*`: TypeScript type definitions
- `ts-loader`: TypeScript compilation for webpack
- `typescript`: TypeScript compiler

### Testing Setup
- `@types/supertest`: Supertest type definitions
- `jest`: Testing framework
- `supertest`: HTTP assertion library
- `ts-jest`: TypeScript support for Jest

### Code Quality Tools
- `eslint`: Code linting
- `prettier`: Code formatting
- `@eslint/eslintrc`: ESLint configuration
- `@typescript-eslint/eslint-plugin`: TypeScript ESLint plugin
- `@typescript-eslint/parser`: TypeScript ESLint parser
- `eslint-config-prettier`: Disable ESLint rules that conflict with Prettier
- `eslint-plugin-prettier`: ESLint plugin for Prettier
- `typescript-eslint`: TypeScript ESLint

### Git Hooks
- `lint-staged`: Automatically runs linting and formatting on staged files
- `postinstall`: Configures git hooks path to `.githooks`

## Commit Message Guidelines

This project follows a specific commit message format to maintain a clear and consistent commit history. All commit messages must follow this format:

```
<type>: <description>
```

### Commit Types

| Type       | Description |
|------------|-------------|
| feat       | Introduces a new feature or functionality |
| fix        | Fixes a bug or issue |
| docs       | Updates or adds documentation |
| style     | Code style changes (formatting, no logic impact) |
| refactor  | Code changes without fixing bugs or adding features |
| perf      | Improves performance |
| test      | Adds or updates tests |
| build     | Changes build system or dependencies |
| ci        | Updates CI configuration or scripts |
| chore     | Routine tasks (e.g., config updates, minor changes) |
| revert    | Reverts a previous commit |
| env       | Changes related to environment variables or settings |
| hotfix    | Urgent bug fix, often for production |

### Examples

```
feat: add user authentication
fix: resolve login validation issue
docs: update API documentation
style: format code according to style guide
refactor: improve user service structure
perf: optimize database queries
test: add unit tests for auth service
build: update dependencies
ci: add GitHub Actions workflow
chore: update .gitignore
revert: revert accidental file deletion
env: update database connection settings
hotfix: fix critical security vulnerability
```

### Important Notes

- The commit message should be in lowercase
- Keep the description concise but descriptive
- Use the imperative mood ("add" not "added" or "adds")
- Reference issues or pull requests at the end of the message if applicable

## Resources

Check out a few resources that may come in handy when working with NestJS:

- Visit the [NestJS Documentation](https://docs.nestjs.com) to learn more about the framework.
- For questions and support, please visit our [Discord channel](https://discord.gg/G7Qnnhy).
- To dive deeper and get more hands-on experience, check out our official video [courses](https://courses.nestjs.com/).
- Deploy your application to AWS with the help of [NestJS Mau](https://mau.nestjs.com) in just a few clicks.
- Visualize your application graph and interact with the NestJS application in real-time using [NestJS Devtools](https://devtools.nestjs.com).
- Need help with your project (part-time to full-time)? Check out our official [enterprise support](https://enterprise.nestjs.com).
- To stay in the loop and get updates, follow us on [X](https://x.com/nestframework) and [LinkedIn](https://linkedin.com/company/nestjs).
- Looking for a job, or have a job to offer? Check out our official [Jobs board](https://jobs.nestjs.com).

## Support

Nest is an MIT-licensed open source project. It can grow thanks to the sponsors and support by the amazing backers. If you'd like to join them, please [read more here](https://docs.nestjs.com/support).

## Stay in touch

- Author - [Kamil Myśliwiec](https://twitter.com/kammysliwiec)
- Website - [https://nestjs.com](https://nestjs.com/)
- Twitter - [@nestframework](https://twitter.com/nestframework)

## License

Nest is [MIT licensed](https://github.com/nestjs/nest/blob/master/LICENSE).
