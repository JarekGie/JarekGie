# DevOps / AWS / Terraform / FinOps

Porządkuję środowiska AWS, redukuję koszty chmury i przywracam kontrolę nad infrastrukturą.

---

## Co robię

- Optymalizacja kosztów AWS — identyfikacja i eliminacja marnotrawstwa (non-prod, idle resources, NAT Gateway, transfer danych)
- Terraform — porządkowanie, standaryzacja modułów, naprawa state management
- CI/CD — diagnoza i optymalizacja pipeline'ów (GitHub Actions, Jenkins)
- ECS / Kubernetes — debugging, stabilizacja, środowiska produkcyjne
- Naprawiam środowiska które „jakoś działają, ale nikt nie wie jak"

## Typowe problemy które rozwiązuję

- Rachunek AWS rośnie bez wyraźnego powodu
- Wiele środowisk (dev/qa/uat/prod) bez kontroli kosztów i bez tagowania
- Deployment niestabilny lub zajmuje 40+ minut
- Terraform repo którego nikt nie chce tykać
- Infrastruktura stawiana ręcznie z konsoli AWS

## Przykłady wyników

- Redukcja rachunku AWS o ~$4 200/miesiąc — konsolidacja NAT Gateway, VPC endpoints, wyłączenie Multi-AZ na dev
- Pipeline skrócony z 45 do 9 minut — BuildKit cache, równoległe testy, cache zależności
- Wdrożenie S3 backend + DynamoDB locking + osobny state per środowisko — koniec z korupcją stanu i blokowaniem zespołu

## Technologie

AWS · Terraform · ECS · EKS · RDS · GitHub Actions · Jenkins · ArgoCD · CloudFormation · Python

## Certyfikaty

- AWS Certified Solutions Architect – Associate

## Doświadczenie

Pracowałem nad produkcyjnymi środowiskami AWS (ECS, RDS, multi-environment, multi-account).
Przeprowadzałem projekty przez AWS Partner Competency — od gap analysis, przez dokumentację case studies, po review techniczny.

---

## Kontakt

Zazwyczaj zaczynam od krótkiej płatnej sesji diagnostycznej (1–2h) — na koniec wiesz dokładnie co i w jakiej kolejności poprawić.

**LinkedIn:** [linkedin.com/in/jarekgolab](https://www.linkedin.com/in/jarekgolab/)
**Email:** jarek@golab.info.pl
