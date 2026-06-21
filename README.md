# Helm practice
Mono repo with multiple helm repos

Anteriormente ya he practicado y realizo mono repos de helm, por estudio propio, sin embargo este repo estará enfocado en mantener mis estudios del curso de [Helm3 | Udemy](https://www.udemy.com/share/103kiI3@1szxonc_n8EGpaN6n5jRXpYt4LVLVwpobSume723qWSQN5qOfUgO52qVpNtWPThtIA==/), y ya adicionalmente, estarán elementos adicionales personal, para seguir practicando.


# Useful Commands

```bash
# Display all active releases with their information
helm list

# Display detail info for a release
helm status

helm get <notes|manifest|...> <release>

helm show <all|chart|readme|...> <repo>

# Upgrade by properties
helm upgrade --set <property> <release> <repo>

# Upgrade by file
helm upgrade -f <file.yaml> <release> <repo>

# History
helm history <release>

# Rollback
helm rollback <release> <version> # Create a new version base on the rollback version

# Delete
helm uninstall <release>
helm uninstall --dry-run <release>
helm uninstall --keep-history <release>
```
