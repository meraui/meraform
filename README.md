## App Requirement

1. One react component library: FormRender.
   ```html
   <FormRender />
   ```
2. Accepts JSON/JS object/TS object as form schema.
3. Two form schema which have 2 different purposes:
   1. UI Schema
   2. Field Schema
4. UI schema will render the UI of the form:
   1. Field position
   2. Field group
   3. etc.
5. Field schema will render field component together with:
   1. Field name
   2. Field id
   3. Field default value
   4. etc
6. Can cater various rendering and logic conditions.
7. Cannot have strict/rigid styling - to allow flexibility and extensibility.

## App Features

1. Able to do multi-step form.
2. Have multi-step pagination with several position options:
   1. Top
   2. Left
   3. Right
   4. Bottom
   5. Custom
3. Have simple validations.
4. Have complex validations with conditions.
5. Have simple rendering.
6. Have complex rendering with conditions.
7. Have dynamic rendering - eg: field generated through number count
8. Have API generated fields.
9. Have submission logic.
10. Have initial form values population with API calls.

## References

1. JSON Forms: https://jsonforms.io/
