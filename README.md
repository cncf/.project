# .project

Declarative, automated management of CNCF governance bodies and their members.

- [`committees.yaml`](committees.yaml): CNCF committees, their teams and
  members.
- [Validate Committees](.github/workflows/validate-committees.yaml): validates
  `committees.yaml` on every pull request and push to `main`.

See the [schema reference](https://github.com/cncf/automation/blob/main/utilities/dot-project/SCHEMA.md)
for details.