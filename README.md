| **نام فیلد**         | **نوع**       |                                       **شرح** |                **نمونه** |
|----------------------|---------------|----------------------------------------------:|-------------------------:|
| PersianDateKey       | int           |                     کلید اصلی - تاریخ خورشیدی |             **14030306** |
| GregorianDateKey     | int           |                            تاریخ میلادی معادل |             **20240526** |
| FullDate             | char(10)      |                                    تاریخ کامل |           **1403/03/06** |
| Season               | int           |                                     شماره فصل |                    **1** |
| SeasonName           | nvarchar(30)  |                                       نام فصل |                 **بهار** |
| Year                 | int           |                                           سال |                 **1403** |
| Month                | int           |                                     شماره ماه |                    **3** |
| Day                  | int           |                              شماره روز در ماه |                    **6** |
| MonthName            | nvarchar(30)  |                                       نام ماه |                **خرداد** |
| MonthOfSeason        | int           |                                چندمین ماه سال |                    **3** |
| DayName              | nvarchar(20)  |                                  نام روز هفته |               **يكشنبه** |
| ShortDayName         | nvarchar(5)   |                        کوتاه شده نام روز هفته |                    **ی** |
| DayOfWeek            | int           |                               چندمین روز هفته |                    **2** |
| DayOfYear            | int           |                                چندمین روز ماه |                   **68** |
| RemainingDaysOfYear  | int           |                  تعداد روز مانده تا پایان سال |                  **298** |
| DayNameCountInMonth  | int           |                 تعداد این روز هفته در این ماه |                    **4** |
| DayNameCountInYear   | int           |                 تعداد این روز هفته در این سال |                   **52** |
| DayNameCountInSeason | int           |                 تعداد این روز هفته در این فصل |                   **13** |
| WeekOfMonth          | int           |                        چندمین هفته در این ماه |                    **2** |
| WeekOfYear           | int           |                        چندمین هفته در این سال |                   **11** |
| RemainingWeeksOfYear | int           |                 تعداد هفته مانده تا پایان سال |                   **42** |
| WeekOfSeason         | int           |                        چندمین هفته در این فصل |                   **11** |
| WeekCountInMonth     | int           |                         تعداد هفته در این ماه |                    **5** |
| WeekCountInYear      | int           |                         تعداد هفته در این سال |                   **53** |
| WeekCountInSeason    | int           |                         تعداد هفته در این فصل |                   **14** |
| FullDateInf          | nvarchar(100) |                                    تاریخ کامل | **يكشنبه 06 خرداد 1403** |
| SeasonNameYear       | nvarchar(50)  |                                نام فصل \| سال |            **بهار 1403** |
| MonthNameYear        | nvarchar(50)  |                                نام ماه \| سال |           **خرداد 1403** |
| DayMonthNameYear     | nvarchar(50)  |                         نام ماه \| سال \| ماه |        **06 خرداد 1403** |
| YearMonth            | int           |                                    سال \| ماه |               **140303** |
| YYYYMM               | char(7)       |                                    سال \| ماه |              **1403/03** |
| FirstDateInMonth     | char(10)      |                               اولین تاریخ ماه |           **1403/03/01** |
| LastDateInMonth      | char(10)      |                               آخرین تاریخ ماه |           **1403/03/31** |
| FirstDateInSeason    | char(10)      |                        اولین تاریخ در این فصل |           **1403/01/01** |
| LastDateInSeason     | char(10)      |                        آخرین تاریخ در این فصل |           **1403/03/31** |
| FirstDateInYear      | char(10)      |                        اولین تاریخ در این سال |           **1403/01/01** |
| LastDateInYear       | char(10)      |                        آخرین تاریخ در این سال |           **1403/12/30** |
| IsLeapYear           | bit           |                                سال کبیسه است؟ |                    **1** |
| IsHoliday            | bit           |        روز تعطیل است؟  جمعه ها مقدار یک دارند |                    **0** |
| IsWorkDay            | bit           | روز کاری است؟ پنج شنبه و جمعه مقدار صفر دارند |                    **1** |