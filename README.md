
## 파일 구조 - 의존성 방향 ↓↓

<pre>
MyPlanner
│
├── Application
│
├── Presentation 
│   ├── MainTabBarController 
│   ├── Monthly 
│   │        ├── MonthlyViewController 
│   │        └── MonthlyViewModel
│   ├── Weekly
│   │       ├── WeeklyViewController 
│   │       └── WeeklyViewModel
│   └── Daily 
│           ├── DaillyViewController 
│           └── DailyViewModel
│   
├── Domain 
│  
└── Data 
    └── DataSource 
<pre>
