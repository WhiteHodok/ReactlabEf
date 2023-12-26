React + TypeScript + Vite
This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

@vitejs/plugin-react uses Babel for Fast Refresh
@vitejs/plugin-react-swc uses SWC for Fast Refresh
Versions
node: '18.18.0', npm: '10.2.5', typescript: '5.2.2'

Expanding the ESLint configuration
If you are developing a production application, we recommend updating the configuration to enable type aware lint rules:

Configure the top-level parserOptions property like this:
export default {
  // other rules...
  parserOptions: {
    ecmaVersion: 'latest',
    sourceType: 'module',
    project: ['./tsconfig.json', './tsconfig.node.json'],
    tsconfigRootDir: __dirname,
  },
}
Replace plugin:@typescript-eslint/recommended to plugin:@typescript-eslint/recommended-type-checked or plugin:@typescript-eslint/strict-type-checked
Optionally add plugin:@typescript-eslint/stylistic-type-checked
Install eslint-plugin-react and add plugin:react/recommended & plugin:react/jsx-runtime to the extends list
To run you need to...
Have Vite and write npm install + npm run dev

Featurues
Slider + View All works


![292269707-784b5d5e-ea09-4909-897b-4fc0b87df9ad](https://github.com/Infamous999/Reactlab/assets/79654330/fb0ef0f3-b907-42c1-9ae8-b59a9ed1943c)
![292269782-85f71fe5-a913-4d24-acfb-45021655fedb](https://github.com/Infamous999/Reactlab/assets/79654330/4db68d19-840e-47ea-bb10-c3817edf9a40)
![292269869-f48268e3-8721-4932-acdf-ec09c24e9e1d](https://github.com/Infamous999/Reactlab/assets/79654330/938b2ce6-200a-4e9f-b86a-eab6a79c7726)
![292269934-e1252f7c-3ad7-462d-942a-73c2a4d289fd](https://github.com/Infamous999/Reactlab/assets/79654330/7d75ec86-2631-450b-99c5-e7e7388082bd)
![292270003-a1c4c94a-386e-45dc-8cf1-83e3cca5ee34](https://github.com/Infamous999/Reactlab/assets/79654330/74fce711-4b6f-4daa-8d1e-02d93afaff92)
![292270003-a1c4c94a-386e-45dc-8cf1-83e3cca5ee34](https://github.com/Infamous999/Reactlab/assets/79654330/36ccd66b-14a7-4cb5-a9c1-63aa1b12eb84)
![292270064-c8591998-1a6e-402a-b436-6e169e5d5d68](https://github.com/Infamous999/Reactlab/assets/79654330/09c04dbe-e1ba-4786-bbc6-41c0d2a1cdf0)

