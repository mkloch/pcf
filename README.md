# HelloWorld PCF Control

This project is a sample PowerApps Component Framework (PCF) control named **HelloWorld**. It demonstrates the basic structure and lifecycle methods required for a custom PCF control.

## Project Structure

- `HelloWorld/index.ts`: Main TypeScript file implementing the control logic.
- `HelloWorld/ControlManifest.Input.xml`: Manifest file defining control metadata and properties.
- `HelloWorld/generated/ManifestTypes.d.ts`: Type definitions generated from the manifest.
- `pcfconfig.json`: PCF project configuration.
- `tsconfig.json`: TypeScript configuration.
- `package.json`: Project dependencies and scripts.
- `pcf.pcfproj`: Project file for build and deployment.

## Key Files

### `index.ts`
Implements the `HelloWorld` class, which extends `ComponentFramework.StandardControl<IInputs, IOutputs>`. It includes the following lifecycle methods:
- `init`: Initializes the control.
- `updateView`: Updates the control view when data changes.
- `getOutputs`: Returns outputs to the framework.
- `destroy`: Cleans up resources when the control is removed.

## Getting Started

1. **Install dependencies:**
   ```sh
   npm install
   ```
2. **Build the control:**
   ```sh
   npm run build
   ```
3. **Test locally:**
   Use the [Power Apps CLI](https://learn.microsoft.com/power-apps/developer/component-framework/overview) to test and debug your control.

## Resources
- [PCF Documentation](https://learn.microsoft.com/power-apps/developer/component-framework/overview)
- [TypeScript](https://www.typescriptlang.org/)

## License
This project is licensed under the MIT License.
