# DIMPersianDate

## از تاریخ 1300/01/01 تا تاریخ 1500/12/29
## تعداد رکوردها: 73414
##


|        | **نام فیلد**         | **نوع**       |                                       **شرح** |                **نمونه** |
|--------|----------------------|---------------|----------------------------------------------:|-------------------------:|
| **1**  | PersianDateKey       | int           |                     کلید اصلی - تاریخ🔑 خورشیدی |             **14030306** |
| **2**  | GregorianDateKey     | int           |                            تاریخ میلادی معادل |             **20240526** |
| **3**  | FullDate             | char(10)      |                                    تاریخ کامل |           **1403/03/06** |
| **4**  | Season               | int           |                                     شماره فصل |                    **1** |
| **5**  | SeasonName           | nvarchar(30)  |                                       نام فصل |                 **بهار** |
| **6**  | Year                 | int           |                                           سال |                 **1403** |
| **7**  | Month                | int           |                                     شماره ماه |                    **3** |
| **8**  | Day                  | int           |                              شماره روز در ماه |                    **6** |
| **9**  | MonthName            | nvarchar(30)  |                                       نام ماه |                **خرداد** |
| **10** | MonthOfSeason        | int           |                                چندمین ماه سال |                    **3** |
| **11** | DayName              | nvarchar(20)  |                                  نام روز هفته |               **يكشنبه** |
| **12** | ShortDayName         | nvarchar(5)   |                        کوتاه شده نام روز هفته |                    **ی** |
| **13** | DayOfWeek            | int           |                               چندمین روز هفته |                    **2** |
| **14** | DayOfYear            | int           |                                چندمین روز ماه |                   **68** |
| **15** | RemainingDaysOfYear  | int           |                  تعداد روز مانده تا پایان سال |                  **298** |
| **16** | DayNameCountInMonth  | int           |                 تعداد این روز هفته در این ماه |                    **4** |
| **17** | DayNameCountInYear   | int           |                 تعداد این روز هفته در این سال |                   **52** |
| **18** | DayNameCountInSeason | int           |                 تعداد این روز هفته در این فصل |                   **13** |
| **19** | WeekOfMonth          | int           |                        چندمین هفته در این ماه |                    **2** |
| **20** | WeekOfYear           | int           |                        چندمین هفته در این سال |                   **11** |
| **21** | RemainingWeeksOfYear | int           |                 تعداد هفته مانده تا پایان سال |                   **42** |
| **22** | WeekOfSeason         | int           |                        چندمین هفته در این فصل |                   **11** |
| **23** | WeekCountInMonth     | int           |                         تعداد هفته در این ماه |                    **5** |
| **24** | WeekCountInYear      | int           |                         تعداد هفته در این سال |                   **53** |
| **25** | WeekCountInSeason    | int           |                         تعداد هفته در این فصل |                   **14** |
| **26** | FullDateInf          | nvarchar(100) |                                    تاریخ کامل | **يكشنبه 06 خرداد 1403** |
| **27** | SeasonNameYear       | nvarchar(50)  |                                نام فصل \| سال |            **بهار 1403** |
| **28** | MonthNameYear        | nvarchar(50)  |                                نام ماه \| سال |           **خرداد 1403** |
| **29** | DayMonthNameYear     | nvarchar(50)  |                         نام ماه \| سال \| ماه |        **06 خرداد 1403** |
| **30** | YearMonth            | int           |                                    سال \| ماه |               **140303** |
| **31** | YYYYMM               | char(7)       |                                    سال \| ماه |              **1403/03** |
| **32** | FirstDateInMonth     | char(10)      |                               اولین تاریخ ماه |           **1403/03/01** |
| **33** | LastDateInMonth      | char(10)      |                               آخرین تاریخ ماه |           **1403/03/31** |
| **34** | FirstDateInSeason    | char(10)      |                        اولین تاریخ در این فصل |           **1403/01/01** |
| **35** | LastDateInSeason     | char(10)      |                        آخرین تاریخ در این فصل |           **1403/03/31** |
| **36** | FirstDateInYear      | char(10)      |                        اولین تاریخ در این سال |           **1403/01/01** |
| **37** | LastDateInYear       | char(10)      |                        آخرین تاریخ در این سال |           **1403/12/30** |
| **38** | IsLeapYear           | bit           |                                سال کبیسه است؟ |                    **1** |
| **39** | IsHoliday            | bit           |        روز تعطیل است؟  جمعه ها مقدار یک دارند |                    **0** |
| **40** | IsWorkDay            | bit           | روز کاری است؟ پنج شنبه و جمعه مقدار صفر دارند |                    **1** |