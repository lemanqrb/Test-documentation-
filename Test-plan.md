# Test Plan

## 1. Purpose

Simplifai sistemində frontend və backend (API) funksionallığın düzgün işləməsini yoxlamaq

## 2. Saytın aktiv modulları

- Authentication (Login / Token)
- User API
- Data API
- Login səhifəsi

## 3. Testing növləri

- Functional
- Smoke
- Regression
- API testing (Backend)
- UI testing (Frontend)

## 4. Test alətləri

- **Postman** – API request-lərin yoxlanılması  
- **Swagger** – endpoint-lərin baxılması  
- **Browser** – əlavə yoxlamalar üçün  

## 5. Environment

- **OS:** Windows 11, Version 25H2  
- **Browser:** Google Chrome Version 123.x (latest)  
- **API Base URL:** https://smplifai-backend.vercel.app/api  
- **Frontend URL:** https://smplifai-frontend.vercel.app  

## 6. Giriş kriteriyaları

- API-lar hazırdır  
- Test case-lər hazırdır  
- Test mühiti aktivdir  
- Token əldə etmək mümkündür  
- Frontend açılır  

### Exit criteria

- 85% test case-lər passed  
- Critical defectlər yoxdur  

## 7. Risklər

- Saytın işlək vəziyyətdə olmaması  
- Sistem çökməsi  
- QA staff işlək vəziyyətdə olmaması  
- API-lər işləməyə bilər  
- Token və ya autentifikasiya problemləri  
- Frontend və backend arasında əlaqə problemi  

## 8. Resurslar

- QA – Ləman Qurbanova  

## 9. Test deliverables

- Test Summary Report  
- Bug Reports  

## 10. Vaxt

14.04.2026 – 18.04.2026  
