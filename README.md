# Truba Institute of Pharmacy website

Production website: [https://trubapharmacy.com/](https://trubapharmacy.com/)

This Vite + React single-page website provides institute information, courses, admissions, academics, e-learning material, notices, facilities, research, placements and contact information.

## GoDaddy deployment and refresh fix

`public/.htaccess` is copied to `dist/.htaccess` during build. Upload the **contents of `dist/`**, including this hidden `.htaccess` file, to GoDaddy's `public_html`. It returns React's `index.html` for a direct visit or refresh on routes such as `/admission` and `/bpharm-year-3`, but lets actual files such as PDFs load normally. This resolves the GoDaddy 500/error page on refresh.

## Website pages

| Section | URL | What it does |
| --- | --- | --- |
| Home | [/](/) | Institute overview, course highlights and quick links. |
| About | [/about](/about) | Institute information, approvals and policies. |
| Admissions | [/admission](/admission) | Enquiry form, procedure, rules and brochures. |
| Courses | [/courses](/courses) | B.Pharm, M.Pharm and D.Pharm details and syllabi. |
| Academic calendar | [/academic-calendar](/academic-calendar) | Programme-wise academic calendars. |
| Timetable | [/timetable](/timetable) | B.Pharm, M.Pharm and D.Pharm timetables. |
| Faculty | [/faculty](/faculty) | Departments and faculty-directory downloads. |
| B.Pharm Year 2 | [/bpharm-year-2](/bpharm-year-2) | Semester 3 and 4 e-learning resources. |
| B.Pharm Year 3 | [/bpharm-year-3](/bpharm-year-3) | Semester 5 and 6 e-learning resources. |
| Notices | [/notices](/notices) | Current institutional notices. |
| Infrastructure | [/infrastructure](/infrastructure) | Campus facilities and infrastructure document. |
| Research | [/research](/research) | Research and industry-interaction information. |
| Contact | [/contact](/contact) | Institute contact details and enquiry route. |

## PDFs added in the latest update

Every PDF in `public/pdfChnges/` is linked to a public website page and is available through the hosted URL below.

| PDF | Page / purpose | Hosted link |
| --- | --- | --- |
| TIP Brochure | [Admissions](/admission): institute/admission brochure | [Open PDF](https://trubapharmacy.com/pdfChnges/TIP%20Brochure.pdf) |
| TIP Brochure – Copy | [Admissions](/admission): second uploaded brochure copy | [Open PDF](https://trubapharmacy.com/pdfChnges/TIP%20Brochure%20%281%29.pdf) |
| Faculty list 2026–2027 | [Faculty](/faculty): current faculty directory | [Open PDF](https://trubapharmacy.com/pdfChnges/Faculty%20list%202026-2027.pdf) |
| BP405T Pharmacognosy & Phytochemistry I | [B.Pharm Year 2](/bpharm-year-2), Semester 4 notes | [Open PDF](https://trubapharmacy.com/pdfChnges/BP%20405%20T%20Pharmacognosy%20and%20phytochemistry%20I.pdf) |
| BP405T Pharmacognosy & Phytochemistry I – Copy | [B.Pharm Year 2](/bpharm-year-2), Semester 4 alternate copy | [Open PDF](https://trubapharmacy.com/pdfChnges/BP%20405%20T%20Pharmacognosy%20and%20phytochemistry%20I%20%281%29.pdf) |
| BP502T Industrial Pharmacy I | [B.Pharm Year 3](/bpharm-year-3), Semester 5 notes | [Open PDF](https://trubapharmacy.com/pdfChnges/BP502T_Industrial_Pharmacy_I_Elearning_Material%20%281%29.pdf) |
| BP504T E-learning material | [B.Pharm Year 3](/bpharm-year-3), Semester 5 notes | [Open PDF](https://trubapharmacy.com/pdfChnges/BP504%20T%20E%20learning%20material.pdf) |

## Other PDF libraries

| Folder | Website usage |
| --- | --- |
| `public/trubapdf/` | Current calendars, timetables, newsletters, committee documents, syllabus and admission rules. |
| `public/PDF/` | Institutional documents, MOU, infrastructure and selected e-learning notes. |
| `public/images/acedemic/` | Historical calendars/timetables plus academic and attendance rules. |
| `public/images/trainingData/` | Syllabi, affiliation/MOU, training and placement records. |
| `public/images/placementData/` | Career guidance and historical placement reports. |
| `public/images/about/` | Policies, outcomes, IIC, IAEC and anti-ragging documents. |

## Commands

```bash
npm install
npm run dev
npm run build
npm run lint
```

## Complete public PDF catalog

All **149** PDFs currently stored under `public/` are listed below. Each URL is the production path after deploying `dist/`; a file with spaces or parentheses is already URL-encoded.

### `public/images/`

- [images\MOU.pdf](https://trubapharmacy.com/images/MOU.pdf)
- [images\nbr-e-sar.pdf](https://trubapharmacy.com/images/nbr-e-sar.pdf)
- [images\nirf-data.pdf](https://trubapharmacy.com/images/nirf-data.pdf)
- [images\about\Graduate Attributes.pdf](https://trubapharmacy.com/images/about/Graduate%20Attributes.pdf)
- [images\about\Leave Policy.pdf](https://trubapharmacy.com/images/about/Leave%20Policy.pdf)
- [images\about\News Letter.pdf](https://trubapharmacy.com/images/about/News%20Letter.pdf)
- [images\about\Programme educational objectives.pdf](https://trubapharmacy.com/images/about/Programme%20educational%20objectives.pdf)
- [images\about\Programme Outcomes.pdf](https://trubapharmacy.com/images/about/Programme%20Outcomes.pdf)
- [images\about\Anti-Ragging\anti ragging.jpeg.pdf](https://trubapharmacy.com/images/about/Anti-Ragging/anti%20ragging.jpeg.pdf)
- [images\about\Anti-Ragging\Antiragging committee.pdf](https://trubapharmacy.com/images/about/Anti-Ragging/Antiragging%20committee.pdf)
- [images\about\Anti-Ragging\Antiragging squad.pdf](https://trubapharmacy.com/images/about/Anti-Ragging/Antiragging%20squad.pdf)
- [images\about\IAEC\New Form BFeb_2022 (1).pdf](https://trubapharmacy.com/images/about/IAEC/New%20Form%20BFeb_2022%20(1).pdf)
- [images\about\IAEC\Proforma for Submission of Minutes of IAEC Meeting.pdf](https://trubapharmacy.com/images/about/IAEC/Proforma%20for%20Submission%20of%20Minutes%20of%20IAEC%20Meeting.pdf)
- [images\about\IIC\Composition of IIC.pdf](https://trubapharmacy.com/images/about/IIC/Composition%20of%20IIC.pdf)
- [images\about\IIC\IIC COMMITTEE.pdf](https://trubapharmacy.com/images/about/IIC/IIC%20COMMITTEE.pdf)
- [images\about\IIC\iic new calendar 2022-23.pdf](https://trubapharmacy.com/images/about/IIC/iic%20new%20calendar%202022-23.pdf)
- [images\about\IIC\IIC ROLES AND RESPONSIBILITY.pdf](https://trubapharmacy.com/images/about/IIC/IIC%20ROLES%20AND%20RESPONSIBILITY.pdf)
- [images\acedemic\Academic Rules.pdf](https://trubapharmacy.com/images/acedemic/Academic%20Rules.pdf)
- [images\acedemic\Attendance Rules.pdf](https://trubapharmacy.com/images/acedemic/Attendance%20Rules.pdf)
- [images\acedemic\acedmic calender\Acad cal jan june 2024.pdf](https://trubapharmacy.com/images/acedemic/acedmic%20calender/Acad%20cal%20jan%20june%202024.pdf)
- [images\acedemic\acedmic calender\Academic calender 2024-25.pdf](https://trubapharmacy.com/images/acedemic/acedmic%20calender/Academic%20calender%202024-25.pdf)
- [images\acedemic\acedmic calender\B.Pharm academic calendar  July -dec 2022.pdf](https://trubapharmacy.com/images/acedemic/acedmic%20calender/B.Pharm%20academic%20calendar%20%20July%20-dec%202022.pdf)
- [images\acedemic\acedmic calender\B.Pharm academic calendarJAN-JUNE 2023.pdf](https://trubapharmacy.com/images/acedemic/acedmic%20calender/B.Pharm%20academic%20calendarJAN-JUNE%202023.pdf)
- [images\acedemic\acedmic calender\B.Pharm Academic Calender 22-23.pdf](https://trubapharmacy.com/images/acedemic/acedmic%20calender/B.Pharm%20Academic%20Calender%2022-23.pdf)
- [images\acedemic\acedmic calender\B.Pharm Academic calender Jan -Dec 2019.pdf](https://trubapharmacy.com/images/acedemic/acedmic%20calender/B.Pharm%20Academic%20calender%20Jan%20-Dec%202019.pdf)
- [images\acedemic\acedmic calender\B.Pharm Academic Calender Jan -Dec 2022.pdf](https://trubapharmacy.com/images/acedemic/acedmic%20calender/B.Pharm%20Academic%20Calender%20Jan%20-Dec%202022.pdf)
- [images\acedemic\acedmic calender\B.Pharm Academic Calender Jan-Dec 2020.pdf](https://trubapharmacy.com/images/acedemic/acedmic%20calender/B.Pharm%20Academic%20Calender%20Jan-Dec%202020.pdf)
- [images\acedemic\acedmic calender\B.Pharm Academic Calender July-Dec 2021.pdf](https://trubapharmacy.com/images/acedemic/acedmic%20calender/B.Pharm%20Academic%20Calender%20July-Dec%202021.pdf)
- [images\acedemic\acedmic calender\D.Pharm Academic Calender 20-21.pdf](https://trubapharmacy.com/images/acedemic/acedmic%20calender/D.Pharm%20Academic%20Calender%2020-21.pdf)
- [images\acedemic\acedmic calender\D.Pharm Academic Calender 21-22.pdf](https://trubapharmacy.com/images/acedemic/acedmic%20calender/D.Pharm%20Academic%20Calender%2021-22.pdf)
- [images\acedemic\acedmic calender\D.Pharm Academic Calender 22-23.pdf](https://trubapharmacy.com/images/acedemic/acedmic%20calender/D.Pharm%20Academic%20Calender%2022-23.pdf)
- [images\acedemic\acedmic calender\D.Pharm Acadrmic Calender 2019-2020.pdf](https://trubapharmacy.com/images/acedemic/acedmic%20calender/D.Pharm%20Acadrmic%20Calender%202019-2020.pdf)
- [images\acedemic\acedmic calender\D.pharm.pdf](https://trubapharmacy.com/images/acedemic/acedmic%20calender/D.pharm.pdf)
- [images\acedemic\acedmic calender\M.Pharm Academic Calender 2019.pdf](https://trubapharmacy.com/images/acedemic/acedmic%20calender/M.Pharm%20Academic%20Calender%202019.pdf)
- [images\acedemic\acedmic calender\M.pharm Academic Calender July -Dec 2021.pdf](https://trubapharmacy.com/images/acedemic/acedmic%20calender/M.pharm%20Academic%20Calender%20July%20-Dec%202021.pdf)
- [images\acedemic\acedmic calender\M.Pharm Academic Calender July-Dec 2020.pdf](https://trubapharmacy.com/images/acedemic/acedmic%20calender/M.Pharm%20Academic%20Calender%20July-Dec%202020.pdf)
- [images\acedemic\acedmic calender\M.Pharm Academic Calender july-Dec 2022.pdf](https://trubapharmacy.com/images/acedemic/acedmic%20calender/M.Pharm%20Academic%20Calender%20july-Dec%202022.pdf)
- [images\acedemic\acedmic calender\M.Pharm Academic Calender June -Dec 2019.pdf](https://trubapharmacy.com/images/acedemic/acedmic%20calender/M.Pharm%20Academic%20Calender%20June%20-Dec%202019.pdf)
- [images\acedemic\time table\DocScanner Aug 18, 2023 4-12 PM.pdf](https://trubapharmacy.com/images/acedemic/time%20table/DocScanner%20Aug%2018%2C%202023%204-12%20PM.pdf)
- [images\acedemic\time table\jan - June 2019 b.pharm.pdf](https://trubapharmacy.com/images/acedemic/time%20table/jan%20-%20June%202019%20b.pharm.pdf)
- [images\acedemic\time table\jan- June 2020 bpharm.pdf](https://trubapharmacy.com/images/acedemic/time%20table/jan-%20June%202020%20bpharm.pdf)
- [images\acedemic\time table\July-Dec 19 bpharm.pdf](https://trubapharmacy.com/images/acedemic/time%20table/July-Dec%2019%20bpharm.pdf)
- [images\acedemic\time table\time table   July -dec 2022.pdf](https://trubapharmacy.com/images/acedemic/time%20table/time%20table%20%20%20July%20-dec%202022.pdf)
- [images\acedemic\time table\Time table  M.pharm , 2 sem , Jan-june 2019.pdf](https://trubapharmacy.com/images/acedemic/time%20table/Time%20table%20%20M.pharm%20%2C%202%20sem%20%2C%20Jan-june%202019.pdf)
- [images\acedemic\time table\Time Table 2024-2025.pdf](https://trubapharmacy.com/images/acedemic/time%20table/Time%20Table%202024-2025.pdf)
- [images\acedemic\time table\Time Table D.pharm 2019-2020 , 1 year.pdf](https://trubapharmacy.com/images/acedemic/time%20table/Time%20Table%20D.pharm%202019-2020%20%2C%201%20year.pdf)
- [images\acedemic\time table\Time table D.Pharm 2020-2021 , 1 and 2 year.pdf](https://trubapharmacy.com/images/acedemic/time%20table/Time%20table%20D.Pharm%202020-2021%20%2C%201%20and%202%20year.pdf)
- [images\acedemic\time table\Time table D.Pharm 2021-2022, 1 year.pdf](https://trubapharmacy.com/images/acedemic/time%20table/Time%20table%20D.Pharm%202021-2022%2C%201%20year.pdf)
- [images\acedemic\time table\Time table D.Pharm 2021-2022, 2 year.pdf](https://trubapharmacy.com/images/acedemic/time%20table/Time%20table%20D.Pharm%202021-2022%2C%202%20year.pdf)
- [images\acedemic\time table\Time table D.Pharm 2022- 2023 , 2 year.pdf](https://trubapharmacy.com/images/acedemic/time%20table/Time%20table%20D.Pharm%202022-%202023%20%2C%202%20year.pdf)
- [images\acedemic\time table\TIME TABLE JAN-JUNE 2023.pdf](https://trubapharmacy.com/images/acedemic/time%20table/TIME%20TABLE%20JAN-JUNE%202023.pdf)
- [images\acedemic\time table\Time table M.pharm , 1 and 3 sem , July- Dec 2019.pdf](https://trubapharmacy.com/images/acedemic/time%20table/Time%20table%20M.pharm%20%2C%201%20and%203%20sem%20%2C%20July-%20Dec%202019.pdf)
- [images\acedemic\time table\Time table M.Pharm ,1 sem, July Dec 2021.pdf](https://trubapharmacy.com/images/acedemic/time%20table/Time%20table%20M.Pharm%20%2C1%20sem%2C%20July%20Dec%202021.pdf)
- [images\acedemic\time table\Time table M.Pharm ,2 sem, Jan- June 2022.pdf](https://trubapharmacy.com/images/acedemic/time%20table/Time%20table%20M.Pharm%20%2C2%20sem%2C%20Jan-%20June%202022.pdf)
- [images\acedemic\time table\Time table M.Pharm ,3 sem, July- Dec 2021.pdf](https://trubapharmacy.com/images/acedemic/time%20table/Time%20table%20M.Pharm%20%2C3%20sem%2C%20July-%20Dec%202021.pdf)
- [images\acedemic\time table\Time table M.pharm 1 and 3 sem , July- Dec 2020.pdf](https://trubapharmacy.com/images/acedemic/time%20table/Time%20table%20M.pharm%201%20and%203%20sem%20%2C%20July-%20Dec%202020.pdf)
- [images\acedemic\time table\TT July  Dec 2024 .pdf](https://trubapharmacy.com/images/acedemic/time%20table/TT%20July%20%20Dec%202024%20.pdf)
- [images\committes\anti discreminatin cell.pdf](https://trubapharmacy.com/images/committes/anti%20discreminatin%20cell.pdf)
- [images\committes\Anti discrimination cell (1).pdf](https://trubapharmacy.com/images/committes/Anti%20discrimination%20cell%20(1).pdf)
- [images\committes\gender sensitization cell.pdf](https://trubapharmacy.com/images/committes/gender%20sensitization%20cell.pdf)
- [images\committes\gender sensitization.pdf](https://trubapharmacy.com/images/committes/gender%20sensitization.pdf)
- [images\committes\greiviance redressal cell.pdf](https://trubapharmacy.com/images/committes/greiviance%20redressal%20cell.pdf)
- [images\committes\industry interaction cell.pdf](https://trubapharmacy.com/images/committes/industry%20interaction%20cell.pdf)
- [images\committes\innovation cell.pdf](https://trubapharmacy.com/images/committes/innovation%20cell.pdf)
- [images\committes\internal complaint committee.pdf](https://trubapharmacy.com/images/committes/internal%20complaint%20committee.pdf)
- [images\committes\ipr cell.pdf](https://trubapharmacy.com/images/committes/ipr%20cell.pdf)
- [images\committes\mandatory disclosure (1).pdf](https://trubapharmacy.com/images/committes/mandatory%20disclosure%20(1).pdf)
- [images\committes\MOU (1).pdf](https://trubapharmacy.com/images/committes/MOU%20(1).pdf)
- [images\committes\physical instructor.pdf](https://trubapharmacy.com/images/committes/physical%20instructor.pdf)
- [images\committes\physical trainer.pdf](https://trubapharmacy.com/images/committes/physical%20trainer.pdf)
- [images\committes\qa committee.pdf](https://trubapharmacy.com/images/committes/qa%20committee.pdf)
- [images\committes\Student counselor.pdf](https://trubapharmacy.com/images/committes/Student%20counselor.pdf)
- [images\placementData\2016-2020 placements.pdf](https://trubapharmacy.com/images/placementData/2016-2020%20placements.pdf)
- [images\placementData\2017-2021 placements.pdf](https://trubapharmacy.com/images/placementData/2017-2021%20placements.pdf)
- [images\placementData\2018-2022 placements.pdf](https://trubapharmacy.com/images/placementData/2018-2022%20placements.pdf)
- [images\placementData\career_guidance_cell.pdf](https://trubapharmacy.com/images/placementData/career_guidance_cell.pdf)
- [images\trainingData\2016.pdf](https://trubapharmacy.com/images/trainingData/2016.pdf)
- [images\trainingData\2017.pdf](https://trubapharmacy.com/images/trainingData/2017.pdf)
- [images\trainingData\2018.pdf](https://trubapharmacy.com/images/trainingData/2018.pdf)
- [images\trainingData\2019.pdf](https://trubapharmacy.com/images/trainingData/2019.pdf)
- [images\trainingData\Affilation & MOU details.pdf](https://trubapharmacy.com/images/trainingData/Affilation%20%26%20MOU%20details.pdf)
- [images\trainingData\B.Pharm Syllabus.pdf](https://trubapharmacy.com/images/trainingData/B.Pharm%20Syllabus.pdf)
- [images\trainingData\D.Pharm Syllabus.pdf](https://trubapharmacy.com/images/trainingData/D.Pharm%20Syllabus.pdf)
- [images\trainingData\Faculty list 2024-2025.pdf](https://trubapharmacy.com/images/trainingData/Faculty%20list%202024-2025.pdf)
- [images\trainingData\INDUSTRIAL TRAINING RECORD 2020-2024.pdf](https://trubapharmacy.com/images/trainingData/INDUSTRIAL%20TRAINING%20RECORD%202020-2024.pdf)
- [images\trainingData\M.Pharm Syllabus (Pharmaceutics & Pharmacology).pdf](https://trubapharmacy.com/images/trainingData/M.Pharm%20Syllabus%20(Pharmaceutics%20%26%20Pharmacology).pdf)
- [images\trainingData\placement_data_2019-2023_batch.pdf](https://trubapharmacy.com/images/trainingData/placement_data_2019-2023_batch.pdf)
- [images\trainingData\placement_data_2020-2024_batch.pdf](https://trubapharmacy.com/images/trainingData/placement_data_2020-2024_batch.pdf)

### `public/PDF/`

- [PDF\BP 405T Pharmacognosy & Phytochemistry I.pdf](https://trubapharmacy.com/PDF/BP%20405T%20Pharmacognosy%20%26%20Phytochemistry%20I.pdf)
- [PDF\BP 603T Herbal Drug Technology.pdf](https://trubapharmacy.com/PDF/BP%20603T%20Herbal%20Drug%20Technology.pdf)
- [PDF\BP 704 T Novel Drug Delivery Systems.pdf](https://trubapharmacy.com/PDF/BP%20704%20T%20Novel%20Drug%20Delivery%20Systems.pdf)
- [PDF\BP101T Human Anatomy & Physiology I.pdf](https://trubapharmacy.com/PDF/BP101T%20Human%20Anatomy%20%26%20Physiology%20I.pdf)
- [PDF\Grevience redresal comittee.pdf](https://trubapharmacy.com/PDF/Grevience%20redresal%20comittee.pdf)
- [PDF\Industry institute intraction cell.pdf](https://trubapharmacy.com/PDF/Industry%20institute%20intraction%20cell.pdf)
- [PDF\infrastructure details website.pdf](https://trubapharmacy.com/PDF/infrastructure%20details%20website.pdf)
- [PDF\Innovation cell.pdf](https://trubapharmacy.com/PDF/Innovation%20cell.pdf)
- [PDF\Intelltual property right cell.pdf](https://trubapharmacy.com/PDF/Intelltual%20property%20right%20cell.pdf)
- [PDF\Internal complaint committee.pdf](https://trubapharmacy.com/PDF/Internal%20complaint%20committee.pdf)
- [PDF\Internal quality assurance committee.pdf](https://trubapharmacy.com/PDF/Internal%20quality%20assurance%20committee.pdf)
- [PDF\MOU.pdf](https://trubapharmacy.com/PDF/MOU.pdf)
- [PDF\SC-ST cell.pdf](https://trubapharmacy.com/PDF/SC-ST%20cell.pdf)
- [PDF\Student counselling cell.pdf](https://trubapharmacy.com/PDF/Student%20counselling%20cell.pdf)

### `public/pdfChnges/`

- [pdfChnges\BP 405 T Pharmacognosy and phytochemistry I (1).pdf](https://trubapharmacy.com/pdfChnges/BP%20405%20T%20Pharmacognosy%20and%20phytochemistry%20I%20(1).pdf)
- [pdfChnges\BP 405 T Pharmacognosy and phytochemistry I.pdf](https://trubapharmacy.com/pdfChnges/BP%20405%20T%20Pharmacognosy%20and%20phytochemistry%20I.pdf)
- [pdfChnges\BP502T_Industrial_Pharmacy_I_Elearning_Material (1).pdf](https://trubapharmacy.com/pdfChnges/BP502T_Industrial_Pharmacy_I_Elearning_Material%20(1).pdf)
- [pdfChnges\BP504 T E learning material.pdf](https://trubapharmacy.com/pdfChnges/BP504%20T%20E%20learning%20material.pdf)
- [pdfChnges\Faculty list 2026-2027.pdf](https://trubapharmacy.com/pdfChnges/Faculty%20list%202026-2027.pdf)
- [pdfChnges\TIP Brochure (1).pdf](https://trubapharmacy.com/pdfChnges/TIP%20Brochure%20(1).pdf)
- [pdfChnges\TIP Brochure.pdf](https://trubapharmacy.com/pdfChnges/TIP%20Brochure.pdf)

### `public/trubapdf/`

- [trubapdf\Acad Calander B.Pharm Jan June 25.pdf](https://trubapharmacy.com/trubapdf/Acad%20Calander%20B.Pharm%20Jan%20June%2025.pdf)
- [trubapdf\Admission Rule Book (1).pdf](https://trubapharmacy.com/trubapdf/Admission%20Rule%20Book%20(1).pdf)
- [trubapdf\Admission Rule Book.pdf](https://trubapharmacy.com/trubapdf/Admission%20Rule%20Book.pdf)
- [trubapdf\All Institutional Commiittees.pdf](https://trubapharmacy.com/trubapdf/All%20Institutional%20Commiittees.pdf)
- [trubapdf\ANTI DISCRIMINATION CELL.pdf](https://trubapharmacy.com/trubapdf/ANTI%20DISCRIMINATION%20CELL.pdf)
- [trubapdf\Anti Ragging Commiittee.pdf](https://trubapharmacy.com/trubapdf/Anti%20Ragging%20Commiittee.pdf)
- [trubapdf\Anti Ragging Squad.pdf](https://trubapharmacy.com/trubapdf/Anti%20Ragging%20Squad.pdf)
- [trubapdf\B.pharm Academic calender Jan-jun 2026.pdf](https://trubapharmacy.com/trubapdf/B.pharm%20Academic%20calender%20Jan-jun%202026.pdf)
- [trubapdf\B.Pharm_Syllabus 2026.pdf](https://trubapharmacy.com/trubapdf/B.Pharm_Syllabus%202026.pdf)
- [trubapdf\BP 704 T Novel Drug Delivery System.pdf](https://trubapharmacy.com/trubapdf/BP%20704%20T%20Novel%20Drug%20Delivery%20System.pdf)
- [trubapdf\BP502T_Industrial_Pharmacy_I_Elearning_Material.pdf](https://trubapharmacy.com/trubapdf/BP502T_Industrial_Pharmacy_I_Elearning_Material.pdf)
- [trubapdf\BP605T_Biotechnology_Elearning_Material.pdf](https://trubapharmacy.com/trubapdf/BP605T_Biotechnology_Elearning_Material.pdf)
- [trubapdf\BP703T PHARMACY PRACTICE.pdf](https://trubapharmacy.com/trubapdf/BP703T%20PHARMACY%20PRACTICE.pdf)
- [trubapdf\BP803T Cosmetic Technology.pdf](https://trubapharmacy.com/trubapdf/BP803T%20Cosmetic%20Technology.pdf)
- [trubapdf\BP804T_Pharmacovigilance_E_Learning_Material.pdf](https://trubapharmacy.com/trubapdf/BP804T_Pharmacovigilance_E_Learning_Material.pdf)
- [trubapdf\Bpharm July dec 2025.pdf](https://trubapharmacy.com/trubapdf/Bpharm%20July%20dec%202025.pdf)
- [trubapdf\Faculty list 2026-2027.pdf](https://trubapharmacy.com/trubapdf/Faculty%20list%202026-2027.pdf)
- [trubapdf\GENDER SENSITIZATION CELL .pdf](https://trubapharmacy.com/trubapdf/GENDER%20SENSITIZATION%20CELL%20.pdf)
- [trubapdf\GREIVANCE REDRESSAL CELL.pdf](https://trubapharmacy.com/trubapdf/GREIVANCE%20REDRESSAL%20CELL.pdf)
- [trubapdf\IIC Commiittee.pdf](https://trubapharmacy.com/trubapdf/IIC%20Commiittee.pdf)
- [trubapdf\IIC Composition.pdf](https://trubapharmacy.com/trubapdf/IIC%20Composition.pdf)
- [trubapdf\IIC-Calender.pdf](https://trubapharmacy.com/trubapdf/IIC-Calender.pdf)
- [trubapdf\industry interaction cell.pdf](https://trubapharmacy.com/trubapdf/industry%20interaction%20cell.pdf)
- [trubapdf\INNOVATION CELL-CLUB.pdf](https://trubapharmacy.com/trubapdf/INNOVATION%20CELL-CLUB.pdf)
- [trubapdf\Internal Quality Assurance Committee.pdf](https://trubapharmacy.com/trubapdf/Internal%20Quality%20Assurance%20Committee.pdf)
- [trubapdf\IPR CELL.pdf](https://trubapharmacy.com/trubapdf/IPR%20CELL.pdf)
- [trubapdf\News Letter 2022-2023.pdf](https://trubapharmacy.com/trubapdf/News%20Letter%202022-2023.pdf)
- [trubapdf\News letter 2023-24.pdf](https://trubapharmacy.com/trubapdf/News%20letter%202023-24.pdf)
- [trubapdf\News letter 2024-2025.pdf](https://trubapharmacy.com/trubapdf/News%20letter%202024-2025.pdf)
- [trubapdf\News letter 2025-26.pdf](https://trubapharmacy.com/trubapdf/News%20letter%202025-26.pdf)
- [trubapdf\Physical trainer.pdf](https://trubapharmacy.com/trubapdf/Physical%20trainer.pdf)
- [trubapdf\SC-ST Cell.pdf](https://trubapharmacy.com/trubapdf/SC-ST%20Cell.pdf)
- [trubapdf\student counsellor (1).pdf](https://trubapharmacy.com/trubapdf/student%20counsellor%20(1).pdf)
- [trubapdf\student counsellor (2).pdf](https://trubapharmacy.com/trubapdf/student%20counsellor%20(2).pdf)
- [trubapdf\student counsellor.pdf](https://trubapharmacy.com/trubapdf/student%20counsellor.pdf)
- [trubapdf\Time Table  B.pharm  2026.pdf](https://trubapharmacy.com/trubapdf/Time%20Table%20%20B.pharm%20%202026.pdf)
- [trubapdf\Time Table B.Pharm Jan _June 2025.pdf](https://trubapharmacy.com/trubapdf/Time%20Table%20B.Pharm%20Jan%20_June%202025.pdf)
- [trubapdf\Timetable D.Pharm 2025-2026.pdf](https://trubapharmacy.com/trubapdf/Timetable%20D.Pharm%202025-2026.pdf)
- [trubapdf\timetable d.pharm.pdf](https://trubapharmacy.com/trubapdf/timetable%20d.pharm.pdf)
- [trubapdf\Timetable M.Pharm Jan June 2026.pdf](https://trubapharmacy.com/trubapdf/Timetable%20M.Pharm%20Jan%20June%202026.pdf)

## Image storage paths

All images are served from `public/`, so their production URL begins with `https://trubapharmacy.com/`. The image collections are stored at:

- `public/images/` — general pages, logos, home imagery and `favicon.ico`.
- `public/images/about/` — about-page visuals; includes `Anti-Ragging/`, `IAEC/` and `IIC/` subfolders.
- `public/images/admission/` — admission images.
- `public/images/backgrounds/` — reusable page backgrounds.
- `public/images/BOG/` — Board of Governors photographs.
- `public/images/company log/` — company/recruiter logos.
- `public/images/events/` — event graphics.
- `public/images/infrastructure/` and `public/infrastructure/` — campus and infrastructure gallery images.
- `public/images/pharamcy/` — pharmacy/lab images.
- `public/images/slider/` — home-page slider images.
- `public/images/sport&culture/` — sports and cultural-event galleries.
- `public/images/teachers/` — faculty/teacher photographs.
- `public/plugins/google-map/images/` — map marker asset.

Example: `public/images/slider/slider1.jpeg` is hosted at [https://trubapharmacy.com/images/slider/slider1.jpeg](https://trubapharmacy.com/images/slider/slider1.jpeg).
