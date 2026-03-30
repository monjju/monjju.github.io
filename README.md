```bash
❯ kubectl get engineer monjju -o yaml
```
```yaml
apiVersion: v1
kind: Engineer
metadata:
  name: Juan Diego Monje
  location: Barcelona, España
  status: OpenToWork
spec:
  role: Junior DevOps Engineer
  background: IT Support → Cloud Native
  philosophy: "Aprendo rompiendo cosas y entendiéndolas"
  stack:
    containers:    [Kubernetes, Docker, Helm, k3d]
    iac:           [Terraform, AWS, GCP, LocalStack]
    cicd:          [GitHub Actions, ArgoCD, Kustomize]
    security:      [Trivy, Gitleaks, Cosign]
    observability: [Prometheus, Grafana, Loki, Tempo, OpenTelemetry]
    os:            [Linux, Windows Server, Bash]
  projects:
    - name: Kubernetes Platform
      status: ✅ Completado
    - name: CI/CD DevSecOps Pipeline
      status: ✅ Completado
    - name: AWS Infrastructure as Code
      status: ✅ Completado
    - name: GitOps con ArgoCD
      status: ✅ Completado
    - name: Observabilidad con OpenTelemetry
      status: ✅ Completado
  links:
    portfolio:  https://monjju.github.io
    github:     https://github.com/monjju
    linkedin:   https://linkedin.com/in/juan-monje-pulecio
    credly:     https://credly.com/users/juan-diego-monje-pulecio
```
```bash
❯ cat notes.txt
No tengo años de experiencia en producción.
Tengo proyectos reales, decisiones técnicas justificadas
y un historial de commits que habla por mí.

❯ _
```
