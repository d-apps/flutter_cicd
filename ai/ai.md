(feature/* ou bugfix/*)
↓
Push → CI roda (build + test + lint)
↓
Pull Request → develop
↓
Code review manual
↓
Merge → develop → CD roda deploy QA
↓
QA testa
↓
Merge → main → CD roda deploy produção
