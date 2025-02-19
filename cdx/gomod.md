## `cdx:gomod` Namespace Taxonomy

| Namespace             | Description                                                       |
| --------------------- | ----------------------------------------------------------------- |
| `cdx:gomod:build`     | Namespace for build related information.                          |
| `cdx:gomod:build:env` | Namespace for build constraints passed via environment variables. |

## `cdx:gomod:build` Namespace Taxonomy

| Property              | Description           |
| --------------------- | --------------------- |
| `cdx:gomod:build:tag` | Additional build tags |

## `cdx:gomod:build:env` Namespace Taxonomy

| Property                          | Description                                        |
| --------------------------------- | -------------------------------------------------- |
| `cdx:gomod:build:env:GOARCH`      | The target architecture (386, amd64, etc.)         |
| `cdx:gomod:build:env:GOOS`        | The target operating system (linux, windows, etc.) |
| `cdx:gomod:build:env:CGO_ENABLED` | Whether or not CGO is enabled                      |
| `cdx:gomod:build:env:GOVERSION`   | Version of the Go compiler                         |
