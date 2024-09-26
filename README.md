# HRMS Frontend

## Conventions

### 1. Naming Conventions

1. Folder names should be in `kebab-case`

2. `.js, .ts` file names should be in `camelCase`

3. `.jsx, .tsx` file names should be in `PascalCase`

4. Typescript code files end in `.ts`

5. Typescript React components files end in `.tsx`

6. **React** components should have the same name as the file and should have the type: `Component:React.FC` or `Component:React.FC<ComponentProps>`

7. Props should end in `Props`

8. Any other type than props should end in `Type`

### 2. Code Conventions

1. Props are defined as `Interface` and used with the `React.FC<T>` generic type

2. Props are exported with `export` and components with `export default`

3. Any wrapper that needs to wrapp the whole application is used inside `App.tsx`, the `index.tsx` file should remain clean

### 3. CSS Conventions

1. Use **BEM** (Block ELement Modifier), `.<block>__<element>--<modifier>`

2. Any style values that are used all-over the application should be in `variable.scss` as variable, all mixins used should be located in `mixins.scss`
