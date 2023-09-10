### React boiler plate ~ TS

---

### Features

✅ TypeScript
✅ Latest version of react and typescript
✅ Separations of concerns
✅ Separate http tasks
✅ Splitting of pages into multiple sections.
✅ Everything is split into smaller componenets.

### Note

This boiler plate is not yet fully complete and there is no code in the files. However, you can adapt the folder structure. This boiler plate also may not be suitable for all type of projects. However it can be forked and modify according to your own style.

- Boilerplate will be updated with code and all the necessary components to kickstart the your project at a very fast pace.
- Libraries will be updated to the latest version regularly.

### Current versions

- Node `v18.17.0`
- React `v18.2.0`
- TS `v4.9.5`

---

### Folder structure

```bash
src/
├─ @core/
│ ├─ constants/
│ │ ├─ any-constants-go-here
│ ├─ utils/
│ │ ├─ helper-functions/classes-go-here
│ │ ├─ dummy-data.json
│ ├─ config/
│ │ ├─ any-configuration-your-app-may-have
│ ├─ http/
│ │ ├─ api/
│ │ │ ├─ api-routes.ts
│ │ │ ├─ api-endpoints.ts
│ │ ├─ axios/
│ │ │ ├─ get.axios.ts
│ │ │ ├─ post.axios.ts
│ │ ├─ api-error-handler/
│ │ │ ├─ error-handler.ts
│ ├─ router/
│ │ ├─ route-configuration-go-here
│ ├─ redux/
│ │ ├─ user/
│ │ │ ├─ relevant-reducer-actions-go-here
│ │ ├─ store.redux.ts
│ │ ├─ root-reducer.ts
│ ├─ interfaces/
│ │ ├─ any-interfaces-here
├─ @ui/
│ ├─ pages/
│ │ ├─ home/
│ │ │ ├─ sections/
│ │ │ │ ├─ index.sections.tsx
│ │ │ ├─ home.page.tsx
│ │ │ ├─ styles/
├─ shared/
│ ├─ components/
│ │ ├─ Buttons/
│ │ │ ├─ button.component.tsx
│ │ │ ├─ button.component.style.scss
│ ├─ styles/
│ │ ├─ \_breakPoints.scss
│ │ ├─ \_placeHolders.scss
│ │ ├─ \_mixins.scss
│ │ ├─ \_colors.scss
```

### Folder structure outline

- `@core` folder contains all the logic that is not related to the UI of the app.
- `@ui` folder contains all the logic that is related to the UI of the app. The `pages` folder contains the page name and then the splitted section content in the `sections` folder.
- `shared` folder contains the components and scss files that are to be shared throughout the project.

### Last updated

`10 Sep 23`

---

### Libraries installed

- React
- TS

### Versions

#### `0.0.1`

- Initial commit
- updated folder structure
- app not build able - files do not contain any code as of now.

### Author

[Muhammad A.](https://github.com/aliwarraich007 "Muhammad A.") | github

### Contributions

- Any contributions are welcomed.
