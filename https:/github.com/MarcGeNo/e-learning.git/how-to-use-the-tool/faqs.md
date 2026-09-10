---
description: Answers to the most frequently asked questions received at the help desk
icon: seal-question
layout:
  width: default
  title:
    visible: true
  description:
    visible: true
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
  metadata:
    visible: true
  tags:
    visible: true
  actions:
    visible: true
---

# FAQs

{% hint style="info" %}
Use the search engine to find the answer to your question!
{% endhint %}

<details>

<summary> <strong>1 BASIC INFORMATION</strong></summary>

**1.1 What is the Facility ID?**

To facilitate the process of identifying facilities in the Salary Matrix, the tool automatically generates a code (Facility ID) for each new facility created (e.g. #CR001776). The two first letters correspond to the country code.

**1.2 Why does the Salary Matrix work with the previous full calendar year?**

Using payroll data from one complete calendar year:

1. Ensures that the data crosses all production seasons. This means capturing seasonal and migratory labour, which tend to be the most vulnerable.
2. Aligns with most fiscal and tax years.
3. Aligns with most Collective Bargaining agreements which are based on calendar year
4. Aligns with most worker contract agreements which are based on calendar year
5. Aligns with most certification cycles and reference of calendar years
6. Aligns with most Living Wage estimate methodologies, reference based on calendar year

**1.3 Our fiscal year is from April to May. Can I enter the payroll data based on the fiscal year, instead of the calendar year?**

IDH recommends entering payroll data for the full calendar year, as living wage estimates are based on calendar years. However, some certification schemes may allow data entry based on the fiscal year, so if you plan to use the calculations for certification, we recommend verifying this with the certifying body.

**1.4 On our facility, according to the CBA, all workers enjoy 6 days of paid vacation in addition to those required by law. How should the remuneration for these additional 6 days of paid holiday be entered?**

a) If all employees are entitled to these additional days off, add the corresponding hours for these 6 days to the " Minimum number of hours of paid annual leave for a worker" field on the "Basic Information" page. In this case, the total number of vacation weeks is 3, so you should enter = 3 \* regular weekly working hours. Enter the pay for these paid vacation days along with the rest of the salary.

b) If only some employees are entitled to these additional days off, to ensure accurate calculations, these additional days should be treated as paid personal leave, and the corresponding hours should be entered as regular hours worked and the pay as salary received.

**1.5 The facility experienced a flood and was forced to suspend the employment of 25% of the workforce for two months. How should this situation be reflected into the Salary Matrix?**

The period of inactivity must affect all workers of the facility to be considered as unpaid mandatory leave, since this data point is used to calculate the maximum ordinary annual hours of the entire workforce.

Since the facility did not put all contracts on hold, but only some workers, these hours should NOT be considered as "hours of mandatory unpaid leave". If the time off for these workers were entered into the "hours of unpaid mandatory leave" field, the matrix would consider the maximum work time in that year for all workers at the facility to be 10 months and would accordingly adjust the wages of all workers who did not work the full year or part-time to what they would have earned if they had worked 10 months, dividing by twelve to calculate the FTE monthly wage comparable to the reference value.

To ensure correct calculations, for the 25% of the workforce affected, enter the hours of suspended employment as hours worked with 0 wages. These workers will probably show a living wage gap reflecting their particular circumstances.

**1.6 Our farm is closed for 9 months during the non-producting season. Shall we consider the 9 months as a period of unpaid mandatory leave?**

No. The period when the farms are closed and employees are dismissed until the next season shall not be considered as "unpaid mandatory leave".

If these hours were entered as unpaid mandatory leave, the tool would consider them as non-workable hours when extrapolating the remuneration to full-time equivalent, and the comparable remuneration would be lower than it should be. For example, if the production season is 3 months, the tool uses the entered remuneration for these 3 months to calculate the remuneration that would correspond to 12 months of work, and then divides by 12 to get the monthly comparable remuneration. If the hours corresponding to the 9 months were entered as unpaid mandatory leave, the tool would considered that the workers already worked all the workable hours in the year, and would just divide the 3 months remuneration by 12.

Unpaid mandatory leave is only for situations in which all workers are employed by an operative facility but not allowed to work.

</details>

<details>

<summary><strong>2 LIVING WAGE ESTIMATES</strong></summary>

**2.1 Which living wage estimate should I choose?**

IDH recommends to use only living wage values estimated by methodologies recognized by IDH. You can use the IDH [Living Wage Estimate finder](https://salarymatrix.idhtrade.org/benchmark-finder/) to find the estimates available for your region. Please make sure to select the estimate corresponding to the region of the facility and the reporting year. In the event that the chosen reference value is not public data, you will have to purchase access to the value.

**2.2 What shall I do if there are no living wage estimates available for my region and year of interest?**

Note that IDH does not calculate living wages estimates.&#x20;

If there are no estimates available for your region and year in the tool, please contact the [living wage estimate methodologies recognised by IDH](https://www.idhsustainabletrade.com/idh-living-wage-identifier/) to check if they are interested in calculating the estimate.

</details>

<details>

<summary><strong>3 PAYROLL: ENTERING WORKERS</strong></summary>

**3.1 Do I need to enter all the workers, or can I include a sample of workers?**

IDH recommends entering all workers on the facility. This includes:

* All workers in the facility payroll, including office workers and supervisors. An exception can be made for senior management, if their salary is well above Living Wage (i.e. more than twice).
* Workers employed via labor providers or intermediaries (e.g. temporary work agencies, recruiters, labor brokers...).
* Workers performing activities at the facility, on a permanent or routine basis, outsourced to service providers (e.g. canteen, security, maintenance).

However, some certification schemes may have different requirements, so please make sure to check with your auditor.

**3.2 Shall we include apprentices and university students under industrial placements into the Salary Matrix?**

Apprenticeships that are part of a formal training program (such as academic pathways, integration schemes, or skill-building initiatives under social programs) and/or take place under tripartite training agreements rather than regular employment contracts can be excluded from the Salary Matrix. These are considered training roles and, under the living wage methodology, are not expected to meet the living wage as their primary purpose is learning and skill development rather than full employment.

That said, applying living wage principles to apprenticeships is considered a recommended good practice. In many cases, companies that have done so have observed positive returns, including higher retention rates, stronger engagement, and smoother transitions into the regular workforce.

However, if the role forms part of a career progression pathway and falls under a regular employment contract, those workers should be included in the Salary Matrix.

**3.3 Should a self-employed worker, such as a first aid trainer, who occasionally visits the farm (perhaps once a year) be included in the Salary Matrix?**

No. Self-employed workers who provide occasional services, such as a first aid course once a year, do not need to be included. The tool is focused on those services who regularly participate in the operation of the facility, for a certain period of time each year or on a sustained basis. These types of one-off, non-operational services are outside the scope of the tool, although they might be important for the facility overall management.

**3.4 What happens when two production centres share workers, that is, the payroll is unified, but the workers work in two different locations? What impacts would have to combine the workers into a single facility when each production centre sells to different buyers?**

When two production centres are under the same payroll system, have the same salary structure and productivity and are located in the same region (share the same living wage estimate), they can be considered as a single facility.

If a client buys from only one of these two production centres and wants to calculate the living wage gap corresponding to that specific location, the % of time that each worker was at each location must be known and the corresponding calculations must be carried out outside the tool.

The other option is to create two separate facilities and split the hours worked and remuneration received between both facilities, based on the time worked at each location. In this case, the Salary Matrix will adjust the remuneration to full time equivalent and calculate the living wage gap per facility.

**3.5 How should we proceed when the same company name has multiple production centres but only one single packing plant, providing the packing service to all the facilities? How shall we enter the packing workers?**

Packing workers must be included in the calculations of the facility where the packing plant is located. The other facilities only have to include the non-shared personnel and note, in the “Description” field of the “Basic Information” tab, that the packing plant personnel were entered in another facility, indicating the corresponding ID number.

**3.6 What do I need to do if I cannot find a work area that exists in my facility in the drop-down menu for work areas?**

If you do not find a work area that is a good fit, simply select “other” from the drop-down menu.

**3.7 Why do I need to separate men and women for each job category?**

This allows for gender-specific analysis, enabling the identification of living wage gaps that may affect a single gender and might otherwise go unnoticed. It also allows for the identification of potential wage gaps between men and women.

**3.8 If I decide to enter all workers individually in the Salary Matrix instead of by job categories, do I need to list people by name?**

No. Please do not list people by name. We recommend that you assign each worker an internal code (a unique number for example) beforehand and use those codes in this tool.

**3.9 Do I need to enter workers that are in the facility payroll but are not working due to disability status?**

You can exclude them if they did not work during the reporting year, since they were not involved in the facility's operation.

**3.10 How should we handle the effects of high turnover in the tool?**

In the case of high rotation, you can include all employees individually or you can aggregate them for workstations, suming up the hours worked and the remuneration paid to various employees holding a single workstation during the year. If you are aggregating by workstation, any additional remuneration that may be derived from this aggregation shall be excluded, for example, if you are aggregating 3 jobs and your three employees receive a new welcome bonus, you can only include this bonus once.

</details>

<details>

<summary><strong>4 WAGES AND HOURS</strong></summary>

**4.1** **How should I include statutory deductions from pay in the Salary Matrix?**

The statutory deductions from pay corresponding to a living wage salary are already taken into consideration in the living wage estimate. Therefore, gross salaries must be entered in the Salary Matrix.

**4.2 How should I enter statutory payments, such as insurances or contributions to social security schemes and pension funds, made by the employer in the Salary Matrix?**

Employer contributions required by law, such as for social security programs, unemployment insurance, and workers’ compensation/injury insurance should not be included as remuneration because they do not add to disposable income of workers within one year.

Moreover, the impact of these contributions on the cost of living is already considered in the living wage estimation.

**4.3 Fumigators have lower daily work hours due to health and safety regulations. How  should I handle this?**

In order to ensure correct calculations, adjust the ordinary hours worker of these workers to the regular working hours as follows: Ordinary hours worked = standard regular daily work hours \* number of days worked. Otherwise, the tool would inflate the remuneration of these workers to the full-time equivalent.

**4.4 How does the Salary Matrix calculate remuneration for part-time and seasonal/temporary workers?**

The Salary Matrix estimates what would be the monthly remuneration that a part-time or seasonal/temporary worker would make if they were to work full time, all year round, by prorating their remuneration to the standard work week or 48 hours per week, whichever is lower.

You can find more information about the calculation formulas [here](../about-the-idh-salary-matrix/the-formulas.md).

**4.5 Some workers in the facility volunteered to work during their paid annual leave in order to obtain an additional income. How shall this additional remuneration be entered in the Salary Matrix?**

Workers should be able to earn a living wage without having to work during their paid annual leave or holidays. Therefore, the hours worked and the remuneration obtained when working during paid annual leave of public holidays should be considered as overtime.

This is also applicable in the situation when the legislation allows for the total or partial compensation of paid annual leave and holidays with remuneration.

**4.6 Some shift workers must work on weekends or public holidays. Should the remuneration generated during these days be counted as overtime?**

If the work during weekends/public holidays are compensated with paid time-off, the wages/hours shall be considered as ordinary.

If worked weekends/public holidays are not compensated with paid time-off but instead with remuneration (with or without premium), the hours/remuneration shall be considered as overtime.

**4.7 Can we include the cost of compensatory rest days for workers who worked during the weekend as worker remuneration?**

No, compensatory rest days are a form of compensation that does not increase the worker's income, neither reduces the cost of living, and therefore cannot be considered remuneration towards a living wage.

**4.8 If salaries increase in a specific month of the year, how should this be reflected in the Salary Matrix? Should we use the highest value? Or the average?**

The Salary Matrix uses the total remuneration earned during a calendar year, so there is no need to reflect any changes in remuneration. Just enter the total amount received by the worker during the year.

**4.9 How do I proceed if remuneration varies depending on the years of service?**

In this case, you can segregate workers in job categories based on type of job and years of service depending on their salary variation. For example, you can group workers with less than one year service, between 1 year and 3 years of service, between 3 years and 5 years of service, etc.

**4.10 Some workers are paid by piece rather than by time worked, and perform different tasks paid at different rates during a day. How should I enter the wages paid to these workers?**

The Salary Matrix is not designed to work with hourly, daily, weekly or piece rates. Instead, it uses the total compensation received during a full calendar year and the total hours worked during that year, per worker (or the average by job category), to calculate the monthly compensation comparable to the living wage estimate.

Therefore, you do not need to enter piece rates or perform complex calculations to estimate annual salaries from various remuneration rates. Simply enter the wages paid and hours worked during the reporting year for each worker (or the average for a job category) as obtained from the payment system or payroll records, without regard to how these salaries were obtained.

For piece-rate workers, this means that it is necessary to record both the number of overtime hours and the wages generated during those overtime hours since, according to the Anker methodology that requires that living wages be earned during ordinary work hours working at a normal pace, only the remuneration generated during regular working hours shall be considered, excluding incentives for extraordinary productivity.

**4.11 Piece pay rates: How do I need to account for different productivity levels when the workers are paid in ‘per piece’ basis?**

Enter workers individually to address the difference in productivity levels of individual workers.

If that is too difficult, you can group workers into several different groups of "piece-rate workers' based on their average productivity - i.e., piece-rate harvester A; piece-rate harvester B; ect. The productivity does not need to be exactly the same for workers in each group. You can group workers that have a similar range of productivity and then take an average.

However, it is important to remember that, according to the Anker methodology, remuneration must be earned during ordinary hours _working at a normal pace_, so remuneration earned working at an extraordinary pace should not be included.

**4.12 Some full-time workers paid by piece-rate voluntarily work less than weekly legal regular working hours. How shall we handle this in the Salary Matrix?**

Piece rates allowing to earn a living wage when working less than regular working hours are usually linked to very strenuous tasks or to tasks that have an associated health and safety risk. Furthermore, the methodology requires that only remuneration earned while working at a normal pace be included, so it would be incorrect to extrapolate the remuneration of exceptionally productive workers who finish their full-time workday earlier.

For these workers, enter the corresponding legal regular working hours instead of the hours actually worked (standard regular daily work hours \* number of days worked).

**4.13 Can we include the remuneration corresponding to paid leaves (e.g. bereavement, sick, disability, parental and care leaves, seniority days, union representation...) required by law or agreed in a CBA?**

Yes. Consider the hours of these statutory personal leaves as “Regular hours worked” and include their compensations as “Wage earned”.

**4.14 Some workers were on sick leave, paid partly by the facility and partly by the social security. How shall we enter this remuneration in the calculation?**

Include all compensation received by the workers, paid by the employer and from social security systems, as “Wage earned”.

**4.15 Some workers receive income generated in one year at the beginning of the following year. In which year of the data should this income be included?**

For the purposes of the Salary Matrix, the important thing is the year in which the worker received the money and was therefore able to use it to cover his or her costs of a decent life. Therefore, regardless of the year in which the income was generated, it must be included in the year in which the actual payment was made to the worker

**4.16 Some employees, such as those in management positions, are not entitled to overtime pay. How should this be accounted for in the Salary Matrix?**

According to the Anker methodology, employees should receive a living wage without needing to work overtime. Therefore, unpaid overtime hours must be entered as unpaid regular hours so that the tool takes them into account when calculating of comparable remuneration.

**4.17 Is the workday limit weekly or daily? In the case of Colombia, some employees work fewer hours on some days and more on others, but they do not exceed the regular weekly working hours limit. That is, the extra hours worked on one day are compensated with hours not worked on another day, but the weekly working hours do not exceed the legal limit of 44 hours.**&#x20;

Generally, it is weekly, within the limits of the law. In other words, if the legal limit of daily regular hours is exceeded, resulting in overtime pay, these hours must be considered overtime. That is, if the hours are paid as overtime, they must be entered into the Salary Matrix as overtime.

**4.18 Why is it necessary to report overtime hours and their corresponding pay if this information is not used for calculating the living wage gap? What is this information used for?**

The definition of a living wage indicates that remuneration should correspond to regular working hours. The tool does not use overtime hours and their corresponding pay for the calculations, but this information:

* Ensures that overtime hours worked are properly tracked.
* Facilitates the separation of overtime pay from regular hourly pay.
* Facilitates the auditors' verification of the tool's proper implementation.

<mark style="color:$primary;">**4.19 Some facilities calculate ordinary working hours based on clock-in and clock-out times, rather than the actual time worked. This approach may include rest periods taken during the workday. Should these rest periods be considered as part of actual hours worked?**</mark>

<mark style="color:$primary;">Rest breaks during the work shift shall be counted as hours worked. On the other hand, lunch break hours outside the work shift do not count as time worked.</mark>

</details>

<details>

<summary><strong>5 BONUSES</strong></summary>

**5.1 How do I know if a given bonus can or cannot be entered into the calculation? What characteristics must they have to be eligible?**

In order for a bonus to be eligible, it must be a regularly provided bonus. The bonus must be expected by the workers at the start of the season and not be at the discretion of the employer. The worker must be able to anticipate the amount of the bonus that she/he is entitled to. The bonus must be paid in cash. These principles guiding the Salary Matrix are drawn from the Anker Methodology®. More information on how the Anker Methodology approaches bonuses can be found here: https://www.elgaronline.com/view/9781786431455/chapter15.xhtml

* Example of a qualifying bonus that doesn’t change: Workers in Job Category A receive a year-end bonus every year. The bonus is always 10% of the worker's annual wages.
* Example of qualifying bonus that does change: Production, quality and attendance bonuses can vary from day to day. However, the rates and the conditions of the bonuses do not vary and are understood by workers ahead of time.
* Example of a qualifying bonus (in addition to legal requirement): An employer provides a severance package for workers. The employer contributes 10% more than what is legally required AND the workers can access the account at any time and can spend the money in any way they choose, without interest or penalties. The severance package is a national legal requirement. In this case, as long as workers can access and spend the money freely, as described, the 10% contribution over the legal requirement can be included as a bonus in the calculation.
* Example of a non-qualifying bonus (legal requirement): Severance packages as required by law.
* Example of a non-qualifying bonus (at the discretion of the employer): At the end of last year, the facility decided to give all workers a surprise bonus equal to 10% of their wages.
* Example of partially-qualifying bonus: Workers are given productivity bonuses that vary depending on available resources but are guaranteed to be no less than 5% of wages when productivity targets are met. Productivity targets are met every year but were exceeded this year. In this case, the qualifying bonus is 5% only.

**5.2 What shall we do when a non-time dependent bonus is paid in a specific month and the worker joined after or left before the bonus was paid? Can we include it anyway?**

No. Bonuses must be entered only for the workers who received them (the total amount or a proportional part). Otherwise, these bonuses could be assigned to workers who will never have the right to receive them. For example, seasonal workers hired during the high season will never receive the fixed bonuses paid during the low season.

The same guideline applies to in-kind benefits that are granted at a specific time, such as school material allocations.

**5.3 The facility offers incentives to employees whose children have the highest academic average. These are financial rewards paid to approximately 60 students each year. Can these rewards be included in bonuses?**

No, these rewards should not be entered into the calculations. According to the living wage principles, for a bonus to be considered part of the remuneration comparable to a living wage, it must be expected and guaranteed. Rewards linked to children's academic performance do not meet this requirement since the reward is not guaranteed as it does not depend solely on the employee's efforts.

**5.4 Can we include holiday bonuses?**

Holiday bonuses can only be included if they are additional payments to the base salary for time off, that are awarded each year coinciding with a vacation season.

The remuneration corresponding to paid vacation days must be entered as wages.

Unpaid vacations should not be included as bonus since they do not increase take-home pay over what full-time workers earn.

**5.5 Can we include vouchers as bonuses, and if so, how?**

Vouchers can only be included as bonuses if the vouchers are essentially the same as cash and can be easily used to cover any cost that the worker chooses (e.g., housing, recreation, food, etc.).

**5.6 Can low-interest loans which are a benefit to the workers be included as a bonus?**

No. Loans are not eligible. Workers need to be able to meet the costs of a basic but decent standard of living in a given year, and year on year, without needing to rely on loans.

**5.7 Our facility is Fairtrade certified and we provide a yearly premium to workers. Can we enter this premium as a bonus?**

No, the Fairtrade premium is not an integral part of the worker remuneration and therefore it cannot be considered a bonus. The yearly premium can be detailed in the Add Ons/Contributions section, for information only.

**5.8 Can contributions to pension or severance funds be included as a bonus?**

In general, no. This is based on the living wage principle that workers should be able to earn a wage sufficient to meet a basic, decent standard of living within a calendar year, without needing to take out loans. They should also be able to plan for the year.

The only instance where pensions, severance funds and other similar payments may be counted is when an employer contributes amounts to those funds that are above what is required by law. In this case, the amount above the legally required amount can be included \_IF\_the workers can access those funds every year, with no penalties, interest payments, or limitations on how the money is spent \_AND\_workers and their representatives agree that it should count toward wages.

**5.9 Can the advanced severance payments be included as a bonus in the Salary Matrix?**

IDH recommends that severance payments (whether paid in advance or not) are not included as cash bonuses for the following reasons:

1. Severance payments are in principle created to support workers when their contracts are terminated. Such payments are classified as deferred payments that, according to the Anker Methodology®, should not be included in the calculation of prevailing remuneration to be compared with living wage estimates.
2. Advanced severance payments should be in addition to the workers’ capacity to cover living expenses. Due to insufficient wages, workers may find themselves forced to withdraw their severance funds, which could leave them financially vulnerable in the event of job loss. Even if the country’s legislation allows workers the option to cash their severance payments in advance if they so desire (for specific purposes stipulated by law or for whatever use they would like to make of it), and its implementation is in accordance with social dialogue and collective bargaining agreements, workers should still be able to cover their monthly living expenses, without the need to cash their severance payments in advance to do so.
3. Including severance payments (whether advanced or not) as part of monthly remuneration for comparison with living wages is considered non- compliant, according to the IDH auditing guidelines for verifying living wage gaps. In addition, in the banana sector for example, schemes like Fairtrade and Rainforest Alliance consider the inclusion of severance payment in the calculation of prevailing remuneration to be compared with living wages as non-compliance.

The above is a recommendation. Ultimately, it will be important for the user to decide with their allies (supply chain partners, unions, audit bodies, and applicable social compliance programs) how to proceed.

For more information regarding this guidance, please read this [report](https://idh.org/resources/recommendation-about-advanced-severance-payments).

**5.10 Seasonal workers at our site are entitled to severance pay at the termination of their seasonal contract, even if they are hired again in a few months. This payment is a legal requirement. Can it be counted as remuneration towards the calculation of the living wage gaps?**

No. Severance payment should never be included in the calculations as payment toward a living wage. This is because the severance payments are intended to cover costs during periods when workers are out of work or in between jobs. The process of regular hiring and firing of workers creates an unstable work environment and depletes the severance funds available to those workers in the unfortunate event that workers are actually let go indefinitely (for example, if the facility had to close, or if the worker was no longer able to perform their duties).

**5.11 Can profit-sharing be included as a bonus?**

In general, no, since it is not a yearly guaranteed payment. However, some exceptions may be made if profit has consistently been made and shared with employees for several years (e.g., 5 years). In that case, the lowest amount of profit share over an agreed period of time could potentially be included, if agreed upon and accepted as remuneration by workers and their representatives.

**5.12 Attendance-linked bonus: Is this counted towards a living wage?**

Yes, it counts and it can be included as a time-dependant bonus in the bonuses section.

**5.13 Some workers work night shifts. Can the night shift pay supplement be included as a bonus?**

A living wage should be earned in a standard workweek; therefore, night shift pay supplement can only be counted as ordinary remuneration if the night shifts fall within their regular contracted working hours (no overtime). In these cases, the supplement shall be included as wage, rather than as a bonus.

This applies to any other pay supplement derived from special circumstances during regular working hours (e.g. dirty work pay supplement).

**5.14 The facility provides a cash payment in case of birth, death of a family member or marriage. Can these amounts be included in other bonuses?**

No. The benefits can only be included in the calculations if they are granted every year. This is not the case with birth, death or marriage grants and therefore they cannot be considered as remuneration.

**5.15 The facility pays a retroactive bonus when signing a collective bargaining agreement that is paid every two years or four years. Can this payment be included as a bonus in the year in which it was paid?**

If this is common practice in the facility, this payment can be considered as expected and guaranteed, and therefore, the amount can be included as a bonus in the year in which it was paid, for the workers who receive it.

**5.16 Cash allowances are a bonus or an in-kind benefit?**

If workers receive cash allowances instead of benefits, and the worker can spend that allowance in any way they choose (even though it might be meant for a specific purpose), then the cash allowance should be considered a bonus

However, if the worker needs to provide proof that the allowance has been used to pay for a certain purpose (for example, rent receipts or contracts need to be provided to receive the cash allowance) then the amount received by the worker should be entered as an in-kind benefit.

Cash allowances can be included as bonuses if they comply with the general principles, that is, they are guaranteed, are paid during the year and do not require work beyond the ordinary legal working hours. Allowances that are paid only on special occasions, such as funerals, marriages, paternity and similar, shall therefore not be included.

**5.17 In our farm, workers receive a  productivity bonus each month the amount of which varies depending on the amount of mussels produced by the farm that month. ¿How shall we include this payment in the tool?**

To count as remuneration the amounts paid must be predictable and guaranteed. Since this is a variable bonus linked to the facility production and hence not completely guaranteed, we recommend to include the lowest yearly amount paid during the previous 5 years as a non-time dependent bonus.&#x20;

**5.18 If we enter employees individually, is it possible to add cash allowances that a specific employee received during the year?**

Specific allowances that are paid periodically, such as childcare assistance based on the number of children, can be included. However, note that the total amount paid by the employer must be divided among all employees.

This is because the amounts included in the estimated living wage correspond to those of a typical family, and therefore, for the purposes of calculating the wage gap, income dependent on family circumstances must be distributed among all employees.

<mark style="color:$primary;">**5.19 We provide all our employees an anual voucher for a fixed amount. Shall we enter this as a bonus or as an in-kind benefit?**</mark>

<mark style="color:$primary;">If the voucher can be redeemed for any type of good without restriction, then it is equivalent to cash payment and shall be entered as a bonus.</mark>&#x20;

<mark style="color:$primary;">If the voucher can only be redeemed for restricted type of goods, then it can be included as an in-kind benefit, with the proviso that the goods are included in the list of costs considered for the living wage estimation (food, transport...).</mark>

<mark style="color:$primary;">Note that in any case, the voucher should be easily redeemed and appreciated and used by most of the workers.</mark>

</details>

<details>

<summary><strong>6 IN-KIND BENEFITS: ELIGIBILITY</strong></summary>

**6.1 What do I do if an in-kind benefit that complies with the requirements is offered in my facility, but I do not see it listed in the tool?**

In principle, all eligible in-kind benefits are listed in the tool. However, some organizations may provide in-kind benefits reducing the cost of decent living that do not fall in the 6 categories provided in the tool. For example, they can provide clothes for personal use or certain insurances considered as cost in the living wage estimate.

If the IKB in question complies with all the principles for the remuneration, it can be included in any of the categories provided for IKB (except housing). Please take note of the section used, so you can fully explain the IKB value of the chosen category to the auditor.

**6.2 If an in-kind benefit is required by law, can I still include it in the living wage gap calculation?**

The general rule is that the value of in-kind benefits required by law cannot be included as remuneration in the calculation. The reason for this is that living wage estimates typically consider these values by reducing the cost of living. For example, if it is required by law that employers provide free healthcare, the living wage estimate will not consider healthcare expenses as a cost for a decent standard of living thus reducing the estimate.

However, if the living wage estimate does not account for the benefit – for example, because the benefit is required by law only under certain conditions – then the benefit could potentially be included in the living wage gap calculation.

**6.3 Is it necessary to provide in-kind benefits to all employees for them to be included in the Salary Matrix?**

No. In-kind benefits that are only offered to some employees may be included. However, workers who receive the in-kind benefit must be in separate job categories from workers who do not receive the in-kind benefit.

**6.4 What shall we do when an in-kind benefit is provided in a specific month and the worker joined after or left before? Shall we include it anyway since the in-kind benefits must be adjusted to what the worker would receive if he/she had worked the entire year?**

No. In-kind benefits must be entered only for the workers who received them (the total amount or a proportional part). Only in-kind benefits of which the worker received only the proportional part of the time worked (for example free lunch) should be adjusted to full time.

**6.5 Can I include personal protective equipment or uniforms as an in-kind benefit?**

No. Equipment for work such as uniforms or PPE is not included as it does not directly reduce the cost of living for a worker and her or his family.

**6.6 Can we include as an in-kind benefit protective equipment and hand sanitizer to prevent disease transmission?**

No. While these are important provisions provided by the facility, they are variable and unforeseen costs that would not have been included in the basic costs of living used to determine the living wage estimates.

**6.7 Can vouchers be included as in-kind benefits?**

Vouchers can be included as in-kind benefits if they fall into one of the in-kind benefit categories listed in the tool and meet all the other requirements for in-kind benefits.

**6.8 If in-kind benefits are not allowed to be added to the calculation of the living wage gap, why should I provide them to my workers?**

The Salary Matrix does not determine which benefits provided by facilities are of value to workers and the exclusion of some in-kind benefits from the calculations does not mean that workers do not value the benefit. Changes of in-kind benefits should be done with close alignment with workers and worker representatives.

**6.9 The collective agreement provides for one family outing per year. This is a leisure activity that includes activities and transportation. It is highly anticipated and appreciated by workers. Why can't it be included if it's an activity in which the whole family participates?**

Paying for recreational activities, although appreciated and valued by workers, does not reduce the cost of living for families and therefore, based on the principles of the Anker Methodology®, its cost cannot be considered in calculating the comparable remuneration.

**6.10 We provide unemployment insurance to all our workers which is not required by law. Can we include the cost of this insurance as an in-kind benefit?**

No. Unemployment insurance costs are not included in the calculation of living wage estimates according to the Anker Methodology® and, therefore, the cost of this insurance cannot be included under in-kind benefits either.

**6.11 Are the purchases of work clothes that aren't necessarily considered uniforms included as in-kind benefits? For example, T-shirts for workshop employees.**

No. If the clothes are for work, they can't be included. They aren't considered clothing for personal use and, therefore, do not reduce the cost of a decent living.

**6.12 Can the costs of legalizing immigrants be included in the matrix, since without it, the migrant would be unable to work?**

No. The reason these types of costs cannot be included in the matrix is that the tool follows international principles defined by the Anker Methodology®, which establish that only in-kind benefits that directly impact the monthly cost of a decent life for workers and their families, such as housing, food, or healthcare, should be considered.

**6.13 Can Fairtrade Premiums that are used for in-kind benefits be added to the in-kind benefits section?**

Fairtrade Premiums should not be included in in-kind benefits as these are dependent on maintaining certification and can vary by the overall production of a facility. <mark style="color:$primary;">However, the total amount of Fairtrade Premiums recieved and the amounts paid directly to workers in cash or vouchers can be registered as Living Wage Contributions in the Adds-on page. The  tool will show the total amount of the facility living wage gap that is covered by the direct payments to workers in the final report.</mark>

**6.14 Are we allowed to include the cost of sports and recreational facilities in the salary matrix? We currently maintain these facilities for the workers’ and their families use, such as a football field, annual sports day activities, and other recreational areas. These are provided for the benefit of all workers and is accessible at all times, as there are no alternative facilities available for them.**

The cost of sports and recreational facilities or activities cannot be included since it is not a cost usually included in the living wage estimate and, therefore, it does not reduce the cost of a decent living.

</details>

<details>

<summary><strong>7 IN-KIND BENEFITS: FOOD</strong></summary>

**7.1** **If the company offers food but not all workers have access to this benefit, can it still be counted as a living wage benefit?**

Do workers have to pay for food? If so, it cannot be included.

If the meal is free, then the benefit can apply to all workers who have access to it on a regular basis. If some workers have access and others do not, the workers must be separated into different job categories. Only full meals will qualify. The value entered in the tool per worker should be the cost to the employer, if this cost is considered acceptable to the workers and most of the workers make use of the benefit. If the worker pays part of the food, this part needs to be deducted from the cost to the employer.

**7.2 Can the cost of food provided for members of workers' committees or others who are fed during meetings at company expense be included in in- kind benefits?**

If such food is provided regularly, for example, once a month and is expected and appreciated by participants, such cost may be included only for those persons who participated in such meetings. However, the facility must maintain records of participation and expenses incurred and ensure appropriate allocation only to participants of each session, and the cost of maintaining such records may be greater than the benefit of including such amounts in the calculations.

**7.3 Can periodic donations to workers of food produced at the farm (for example, bananas) be included in the salary matrix?**

The cost to the employer of donations of food produced at the farm can be included as an in-kind benefit as long as:

* the type of food is included in the model diet used to estimate the living wage estimate of the region,
* the donations and its monetary value are agreed upon in a collective bargaining agreement and
* are appreciated and valued by the workers.

**7.4 Can payments made by the company to reduce food costs in the canteen (e.g., donating space in the facilities, paying for utilities such as electricity and water, waiving rent, etc.) be included as a benefit in kind? If so, how?**

If employees pay for their meals, these costs should not be included as in-kind benefit.

If the meals are considered subsidized due to these contributions from the employer, the subsidized amount (how much more it would cost the employee to eat in the cafeteria if the company did not make these contributions) must be known and accepted by the employees as in-kind benefit.

</details>

<details>

<summary><strong>8 IN-KIND BENEFITS:  TRANSPORT</strong></summary>

**8.1 The facility offers free transportation to all workers, but not all use it, how should I enter this in-kind benefit?**

For an in-kind benefit to be counted as remuneration, it must be valued and accepted by most of the workers. Therefore, the cost of this free transportation can be included if most workers use and value it, although a few workers do not use it for reasons of convenience.

For benefits that do not affect all workers, such as school and transport the average value over all workers should be used.&#x20;

Two alternatives are offered to enter this in-kind benefit:

* Divide the cost to the employer among all workers with access to transportation and assign it to everyone.
* Divide the cost to the employer among all workers who use it and assign it only to those who use it.

This same principle applies to all in-kind benefits, such as meals.

**8.2 Can I include bicycles as a transportation benefit?**

Yes. The value of bicycles that are provided to workers as a form of transportation may be included in the living wage gap calculation if they meet all the requirements for in-kind benefits. Forms of transportation that are only available for use within the facility cannot be included. The initial cost of the bicycle can be included for one year or divided across multiple years until the initial cost is covered.

**8.3 The facility is in an island, and we provided free transport from land to the island. Can this transport cost be included?**

No. Transport from land to the island should be considered as transport for work unless suitable public transport is available.

</details>

<details>

<summary><strong>9 IN-KIND BENEFITS: CARE</strong> </summary>

**9.1 Can soap and other sanitary products provided for worker use at home be considered as an in-kind benefit?**

Soap and other sanitary products that are provided at the workplace during working hours cannot be included. Packages of soap and sanitary products that are provided to workers to take home could be included under Care, if all other requirements for in-kind benefits (including being an acceptable part of wage payment by workers) are met. However, such packages tend to represent a very small portion of the non-food/non-housing costs.

**9.2 Can the logistics expenses covered by the company to help the worker receive medical treatment be included? For example, transportation costs to the medical centre and food costs during their stay.**

Yes, but only if the medical treatment the worker requires is not related to occupational health. Therefore, the logistical costs of treating occupational illnesses or workplace accidents must be excluded from the cost calculation, and the total calculated cost must be divided among all the workers at the facility.

**9.3 What happens when the employer covers the worker's contribution to social security? Can this be included as remuneration or not?**

If the employer pays the social security contribution payable by the employee, this amount corresponding can be considered as a healthcare in-kind benefit. Note, though that social security contributions to social security payable by the employer cannot be included.

**9.4 We cover the costs of glasses and subsidise psicological attention to employees that ask for it. Can we include these as an in-kind benefit?**

Yes, these any healthcare support beyond what is available thorugh the free public services can be inclued as a healthcare in-kind benefit if it is not work related, but note that the total cost to the employer for these benefits shall be divided among all the workers in the facility.

</details>

<details>

<summary><strong>10 IN-KIND BENEFITS: CHILDREN EDUCATION</strong> </summary>

**10.1 The facility provides a bursary for workers with children to support education depending on the number of children. How shall we enter this amount?**

For benefits that do not affect all workers, such as school and transport the average value over all workers should be used. Thus the example shows that if school costs the employer $3 per student per month, and 2/3 of workers have one child in school, the cost of this benefit to the employer is $2 per worker per month.

**10.2 The facility covers the salary of a teacher at a public school near the farm, which is attended not only by the children of the workers. How can we include this cost?**

The cost should not be included because this contribution to the school's upkeep does not reduce the workers' cost of living.

</details>

<details>

<summary><strong>11 IN-KIND BENEFITS: HEALTHCARE</strong></summary>

**11.1 Foreign workers cannot use public health services, so we are paying for their private health insurance. In such cases, can the employer's contribution be included as part of the worker remuneration? Where?**

The living wage estimate is calculated for workers with access to public health systems and, in principle, is not applicable to foreign workers without access to them. For these workers, the estimated reference value would be higher because the estimate should include the cost of public healthcare or private health insurance.

Including the cost of private health insurance as an in-kind benefit would imply that, with equal access to healthcare, foreign workers have more money available for their monthly expenses than national workers, which does not reflect reality. Providing private health insurance simply balances the health coverage of migrant workers with that of local workers, allowing the use of the same estimated reference value for both.&#x20;

If private healthcare offers benefits superior to those provided by the public healthcare system, the value of healthcare not covered by the public system included in the living wage estimate, adjusted for inflation, could be included as a healthcare in-kind benefit. For example, in the Dominican Republic, the Anker Full-fledged report considers a healthcare cost of USD 37 per month in 2022, which would correspond to USD 39 per month in 2025, based on the inflation applied to update the estimated living wage between 2022 (USD 461) and 2025 (USD 489).

<mark style="color:$primary;">**11.2 The facility makes an annual contribution to each employee's health account. Employees can use the deposited tax-free funds to cover their medical expenses. They can also use them for other purposes if they pay the corresponding taxes on the  contribution received. How should we account for this contribution?**</mark>

<mark style="color:$primary;">Since the workers can use the money deposited in the account to cover any cost, the amount deposited in the account shall entered as a bonus. If the amount deposited is a fixed amount epr year, enter the amount as non-time dependent bonus. If the amount varies depending ont he number of days worked in the reporting year, enter the amount as a time-dependent bonues and the tool will automatically prorate to FTE.</mark>

</details>

<details>

<summary><strong>12</strong> <strong>IN-KIND BENEFITS: HOUSING</strong></summary>

**12.1 For a housing benefit, we give workers the choice either to receive cash or to receive housing. How should this be entered? Should the job categories be split between those who receive cash and those who receive housing?**

If the cash can be used for any purpose the worker chooses, then separate categories for workers receiving a cash allowance should be created and the cash allowance included in the bonus section.

For the workers/categories of workers that receive housing, or a housing voucher that can be used for housing only, the housing/voucher cost should be included in the in-kind benefit section. In both cases, the value of the in-kind benefit should not exceed the value given in cash.

**12.2 What can be included in the cost of employer for housing?**

The cost of housing can include amounts paid for repairs, maintenance, utilities, depreciation, taxes, warranties, and mortgage or loan payments made to build or purchase the home.

If the cost of providing housing per year is not consistent from year to year, an average of at least three years should be used.

**12.3 The facility contributes resources to its foundation to channel funds for improvements to sanitary infrastructure in employees' homes. Is it possible to include these donations as an in-kind benefit for those who receive them under the family housing category?**

It is recommended not to include them because it is not a direct payment from the employer to the employee. It should be noted that to include an amount as an in-kind benefit, employees must be informed beforehand and must accept this amount, which must be guaranteed. Furthermore, it will be difficult for auditors to verify that the foundation has actually invested this amount in sanitary infrastructure improvements, and it should not be included in a single year since it is an infrastructure investment subject to amortization.

</details>

<details>

<summary><strong>13 IN-KIND BENEFITS: COST ALLOCATION</strong> </summary>

**13.1 How shall we evaluate the cost of the benefit per worker?**

You would take the operating cost to the employer and divide it by the number of workers with access to the benefit. In the case of a benefit that is utilized by other community members (e.g. schools or medical facilities), divide the cost to the employer by number of families with access to the benefit.

The cost for a recent investment (i.e., cost of buying a bus, cost to build family housing, etc) should be depreciated and spread across time (starting from the year of expenditure) until the full cost has been covered.

The total cost of any individual benefit, per worker, should not exceed the replacement value for that worker. In other words, the cost of housing cannot exceed what it would cost a worker and her/his family to rent housing of similar quality.

**13.2 What shall we do if there are multiple values for a given in-kind benefit?**

The Salary Matrix allows you to enter different amounts in different job categories. When workers of the same job category receive different values for the same benefit, use the average value (cost to employer / number of workers who qualify for the in-kind benefit).

**13.3 Is there any limitation on the amount of in-kind benefits that I can enter?**

Yes, in-kind benefits are non-monetary benefits such as food, transport or housing provided by the employer that reduce the amount of cash income that workers need for a decent standard of living.

Based on the principles for in-kind benefits outlined in the Anker Methodology®, the Salary Matrix limits the contribution of in-kind benefits to ensure the worker's right to self-determination. The combined total value of in-kind benefits is capped at 30% of total remuneration. Housing is capped at 15% of total remuneration. All other benefits are capped at 10% of total remuneration.

You do not need to do these calculations ahead of time. Simply enter the actual yearly value of in-kind benefits per worker and the tool will cap them automatically.

</details>

<details>

<summary><strong>14 ADD ONS</strong></summary>

**14.1 What if our certification is not listed in the certifications standards section?**

Only sustainability certifications are included in the list. If your sustainability certification is not listed, please contact the helpdesk at [livingwagematrix@idhtrade.org](mailto:livingwagematrix@idhtrade.org).

**14.2 Living wage contributions**

How shall we reflect certification premiums and voluntary contributions from supply chain stakeholders in the Salary Matrix?

Only cash or in-kind benefits paid by the employer and included in the employee pay checks can be entered in the payroll tab. Any extra funds or in-kind benefits received by workers outside their payroll, either coming from supply chain voluntary contributions or certification premiums, shall not count as remuneration towards the calculation of living wage gaps. You can enter these contributions in the Add-ons/Contributions section for information only.

**14.3 We have a client interested in making contributions to reduce the 2024 living wage gap; this payment would be made in 2026. How do we process this benefit? Is it possible to reopen the 2024 matrices to record the voluntary contribution that will be implemented in 2026?**

Taking into account that living wage gap contributions are not included in the calculation of the remuneration since they are not guaranteed and that the Salary Matrix only indicates the percentage of the facility's total gap that such a contribution would cover, IDH recommends to enter them in the year they are received, which is when the worker can use them to afford the cost of a decent living. In this way, the tool will show the living wage gap for 2026 and how it would be reduced thanks to the impact of the contributions received that year, regardless of whether these contributions originate from past product deliveries.

</details>

<details>

<summary><strong>15 REPORT</strong></summary>

**15.1 What does a percentage gap (e.g., 20%) mean in practical terms, and how should it be explained?**

Itmeans that the worker (or workers in the job category) would have received a monthly salary 20% lower than the salary needed to afford a decent standard of living in the region, had they worked full-time for the entire year under the same working conditions.

**15.2 produce several products at my facility with the same workforce. Can I measure the Gap per trade unit for a specific product?**

The Salary Matrix is ​​designed to calculate the pay gap for a worker/job category, regardless of the tasks they perform. Therefore, if the facility produces different products with the same workforce, it is not possible to calculate the gap per trade unit for each product independently.

**15.3 I need to make some corrections to the data entered but I've already submitted my data. How can I re-open the Calculation?**

To re-open a submitted Calculation, go to tab _6. Reports_ and click on the three dots on the top of right to access the _Re-open to edit_ function.

You can also reopen for editing from the Calculations list by clicking on the three dots at the end of the already submitted calculations.

</details>
