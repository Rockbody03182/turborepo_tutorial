# TURBOREPO + TRPC + NEXTJS + SHADCN-UI - 2023.12.14

Getting Started  
`전역설치`
```sh
npm install turbo --global
```
`빠른 프로젝트 생성`
```sh
npx create-turbo@latest
```
√ Where would you like to create your turborepo? ./my-turborepo  
√ Which package manager do you want to use? npm workspaces  
2개의 질문에 답이 끝나면 설치가 시작된다.

yarn, pnpm 설치는 [turbo.build](https://turbo.build/) 홈페이지에서 참고하시길 바랍니다.

`/apps 디렉토리 위치에 server 디렉토리를 생성하고 trpc를 설치한다.`
```sh
npm install @trpc/server @trpc/client express cors
```

```sh
npm install @types/express @types/cors ts-node-dev -D
```

`/packages/ui 위치에 shadcn/ui를 설치한다`
```sh
npx shadcn-ui@latest init
```

√ Ok to proceed? (y)  
√ Would you like to use TypeScript (recommended)?  yes  
√ Which style would you like to use? Default  
√ Which color would you like to use as base color? Slate  
√ Would you like to use CSS variables for colors? yes  
√ Where is your tailwind.config.js located? » tailwind.config.js  
√ Configure the import alias for components: » @/components  
√ Configure the import alias for utils: » @/lib/utils  
√ Are you using React Server Components? yes  
√ Write configuration to components.json. Proceed? Y  
npm install -D taillwindcss postcss autoprefixer