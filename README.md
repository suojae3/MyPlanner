
## 파일 구조

## 전체적인 모듈 구조

<pre>
파일의 의존성 방향 ↓↓
├── Application <br>
├── Presentatino<br>
│   ├── MainTabBarController <br>
│   ├── Monthly <br>
│   │        ├── MonthlyViewController <br>
│   │        └── MonthlyViewModel<br>
│   ├── Weekly <br>
│   │       ├── WeeklyViewController <br>
│   │       └── WeeklyViewModel<br>
│   └── Daily <br>
│           ├── DaillyViewController <br>
│           └── DailyViewModel<br>
│   
├── Domain <br/>
│  
└── Data <br/>
    └── DataSource 
<pre>
