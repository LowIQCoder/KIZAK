---
title: "Week #2"
---

# **Week #2**

## ⚙️ **Detailed Requirements Elaboration**

### 👤 **Detailed User Stories**

* 1. **User Authentication**  
  **As a forgetful user**, I want to **sign up/login with Google/GitHub** so that **I don’t get locked out due to password issues**.  
  
  **Acceptance Criteria**:  
  ✅ Social login options:  
     - Google  
     - GitHub  
     - Apple (for iOS users)  
  ✅ Fallback email magic links  
  ✅ Clear error messages for:  
     - "Email already in use"  
     - "Account locked (too many attempts)"  
  
  **Edge Cases**:  
  ⚠️ My social account gets hacked  
  ⚠️ I need to merge multiple accounts  
  ⚠️ Enterprise SSO required for my team

### 🐗 **Prioritized backlog**

Our current backlog could be found [here](https://github.com/orgs/IU-Capstone-Project-2025/projects/11) 

## Project specific progress

### Design

* Created initial [design](https://www.figma.com/design/Ew8Vmgzn739HYN2aAaVb1s/Untitled?node-id=0-1&t=eC6UcHbY32eWsSUx-1) for:
  * Initial page
  * Onboarding pages
  * Main page with roadmap
  * Options

### Frontend

### Backend

* Created database prototype
* Created base endpoints for
  * User CRUD operations
  * Roadmap CRUD operations (with nodes and links)
  * Resource CRUD operations
* Created documentation for API

### ML

* Training dataset selected

# Weekly commitments

## Individual contribution of each participant

* Marsel Berheev: m.berheev@innopolis.university
  * Weekly report
  * Roadmap API design (see [issue](https://github.com/IU-Capstone-Project-2025/KIZAK/issues/27))

* Maksim Malov: m.malov@innopolis.university
  * CI/CD pipeline initial design (see [last commit](https://github.com/IU-Capstone-Project-2025/KIZAK/commit/b93edec84420d2d8c040653d511f5ae2e2f62dbd))
  * User API design (see [issue](https://github.com/IU-Capstone-Project-2025/KIZAK/issues/18)) ADD COMMITS

* Makar Egorov: m.egorov@innopolis.university
  * Course dataset design (see issue) ADD COMMITS

* Timur Farizunov: t.farizunov@innopolis.university
  * Onboarding and main page design (see corresponding frames in [figma](https://www.figma.com/design/Ew8Vmgzn739HYN2aAaVb1s/Untitled?node-id=0-1&t=eC6UcHbY32eWsSUx-1))
  * Main page design and frontend structure setup (see [commit](https://github.com/IU-Capstone-Project-2025/KIZAK/commit/1cf59a878d99964351fa6d0eefe34f39f559f5c7))

* Sarmat Lutfullin: s.lutfullin@innopolis.university
  * Initial page design (see corresponding frames in [figma](https://www.figma.com/design/Ew8Vmgzn739HYN2aAaVb1s/Untitled?node-id=0-1&t=eC6UcHbY32eWsSUx-1))
  * Initial page frontend
 
* Ulyana Chaikovskaya: u.chaikouskaya@innopolis.university
  * Dataset analisys (see corresponding frame in [miro](https://miro.com/app/board/uXjVIrMw-Nw=/?share_link_id=30918973188) or [issue](https://github.com/IU-Capstone-Project-2025/KIZAK/issues/13))

* Kseniia Khudiakova: k.khudiakova@innopolis.university
  * Dataset analisys (see corresponding frame in [miro](https://miro.com/app/board/uXjVIrMw-Nw=/?share_link_id=30918973188) or [issue](https://github.com/IU-Capstone-Project-2025/KIZAK/issues/13))

## Plan for Next Week

* Finish front end MVP
* Integrate API to MVP
* Update documentation

## Confirmation of the code's operability

We confirm that the code in the main branch:
- [ ] In working condition.
- [ ] Run via docker-compose (or another alternative described in the `README.md`).
