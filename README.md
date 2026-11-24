🇰🇪 Kenya Public Services PWA

Independent Offline-First Public Service Information Platform

An independent, mobile-friendly public information project designed to help people discover national and county government services in Kenya.

About the Project

Kenya Public Services PWA aims to make public service information easier to find, understand and access, especially for people using mobile devices or experiencing limited internet connectivity.

The project covers Kenya's national government services and all 47 county governments.

Project Objectives

1. Improve access to public service information.
2. Organise national and county government service directories.
3. Provide general application guidance and preparation checklists.
4. Link users to relevant official government websites.
5. Develop offline access to selected public information.
6. Promote responsible use of verified information.

Current Features

- Mobile-responsive homepage.
- National government service directory.
- Directory of all 47 counties.
- Search functionality for services and counties.
- General public service preparation checklist.
- Links to selected government websites.
- Online and offline connection status indicator.
- Progressive Web App manifest.
- Initial service-worker implementation and application-shell caching.
- SVG application icon.
- Independent project disclaimer.

Development status: Initial prototype — technical validation in progress.

A web app manifest and service worker are present. Initial offline caching has been implemented, but complete offline operation, installation behaviour, cache-update handling and offline fallback functionality have not yet been fully validated.

Detailed county service information and verified county office directories are not yet available.

National Government Information Sources

Institution| Official Website
eCitizen| https://www.ecitizen.go.ke/
Immigration Services| https://immigration.go.ke/
Kenya Revenue Authority| https://www.kra.go.ke/
Huduma Kenya| https://www.hudumakenya.go.ke/
National Transport and Safety Authority| https://www.ntsa.go.ke/
National Social Security Fund| https://www.nssf.or.ke/
Social Health Authority| https://sha.go.ke/
Office of the Data Protection Commissioner| https://www.odpc.go.ke/

These links are provided for information and reference. Users should verify current procedures directly with the relevant institution.

Kenya's 47 Counties

The intended county directory covers:

1. Mombasa
2. Kwale
3. Kilifi
4. Tana River
5. Lamu
6. Taita Taveta
7. Garissa
8. Wajir
9. Mandera
10. Marsabit
11. Isiolo
12. Meru
13. Tharaka Nithi
14. Embu
15. Kitui
16. Machakos
17. Makueni
18. Nyandarua
19. Nyeri
20. Kirinyaga
21. Murang'a
22. Kiambu
23. Turkana
24. West Pokot
25. Samburu
26. Trans Nzoia
27. Uasin Gishu
28. Elgeyo Marakwet
29. Nandi
30. Baringo
31. Laikipia
32. Nakuru
33. Narok
34. Kajiado
35. Kericho
36. Bomet
37. Kakamega
38. Vihiga
39. Bungoma
40. Busia
41. Siaya
42. Kisumu
43. Homa Bay
44. Migori
45. Kisii
46. Nyamira
47. Nairobi City

Detailed county service information and office contacts will be added progressively after verification.

Development Roadmap

Initial implementation

- [x] Create GitHub repository.
- [x] Develop initial HTML homepage.
- [x] Add national service references.
- [x] Add the 47-county directory.
- [x] Implement basic search.
- [x] Create web app manifest.
- [x] Add initial service-worker implementation.

Technical repairs and validation

- [ ] Repair and validate offline caching.
- [ ] Implement and validate an offline fallback page.
- [ ] Protect unrelated browser caches during service-worker updates.
- [ ] Add and validate standard PNG application icons.
- [ ] Validate manifest and installation behaviour.
- [ ] Test offline reload and navigation.
- [ ] Test installation and offline operation on Android.

Future development

- [ ] Develop individual county information pages.
- [ ] Add verified county office directories.
- [ ] Add service-specific requirements and checklists.
- [ ] Establish information verification and update procedures.
- [ ] Expand accessibility and usability testing.
- [ ] Complete deployment validation.

Technology Stack

- HTML5
- CSS3
- JavaScript
- Progressive Web App technologies
- Service Workers and Cache API
- GitHub for source-code management

Privacy and Responsible Use

The project is intended as a public information directory.

It should not request government account passwords, sensitive personal information or payment credentials.

Users should complete official applications and transactions only through verified government platforms.

The application is intended to cache its own public application files. It does not claim to provide offline access to government account systems, payment services or third-party websites.

Testing and Quality Assurance

The presence of a service worker or manifest does not, by itself, establish that all PWA features work correctly.

The following checks remain necessary:

- Confirm successful application loading over HTTPS.
- Confirm service-worker registration and activation.
- Confirm application-shell caching.
- Confirm offline homepage loading.
- Confirm offline fallback behaviour.
- Confirm cache updates do not delete unrelated same-origin caches.
- Confirm all manifest icons load correctly.
- Test installation and operation using Android Chrome and a desktop browser.

Testing results will be documented after the relevant checks have actually been performed.

Important Disclaimer

Kenya Public Services PWA is an independent public information prototype.

It is not an official website, platform, agency or representative of the Government of Kenya, any county government or any government institution.

The project does not issue government documents, process applications, collect government fees or guarantee the accuracy of third-party information.

Government procedures, requirements, contacts and fees may change. Users must confirm current information with the relevant official institution.

Repository

GitHub: https://github.com/farahbata116-ux/offline-public-services-pwa

Project: Kenya Public Services PWA
Version: 1.0 — Initial Prototype
Status: Independent Development Initiative

---

Learn. Access. Connect.
