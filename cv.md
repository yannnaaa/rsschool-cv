# RESUME
1. **Yana Loverova**
2. **Contact Info:**
  * **Phone number:** +375(29)-319-21-50
  * **E-mail:** yannnaaa@mail.ru
  * **Skype:** yannnaaa82
3. **Personal and professional qualities:**
  * sociability, persistence, accuracy, punctuality, sense of responsibility, analytical mind, teamwork skills, desire to learn;
  * I would like to try myself in programming at a higher level in your company, to realize my potential more. I have an interest in new technologies. There is a desire to keep pace with the times.
4. **Skills:**
  * I’m currently studying HTML5, CSS, JavaScript on my own, using the resources of the Codewars, GitHub, rolling-scopes-school sites.
  * I have initial skills in working with WebStorm, Git, Node.js.
  * I know about automated testing using the Mocha and Chai libraries.
5. **Code examples:**
```javascript
  function extractRanges(nums) {
    let str = '';
    let arr = [];
    let j = 0;

    arr.push(nums[0]);

    for ( let i = 1; i <= nums.length; i++ ) {

      if ( arr[j] + 1 == nums[i] ) {
        arr.push(nums[i]);
        j++;
      } else {

        if ( arr.length > 2 ) {
          str = str + ( str != '' ? ',' : '' )
            + arr[0] + '-' + arr[arr.length - 1];
        } else {
          str = str + ( str != '' ? ',' : '' )
            + arr.join(',');
        }

        arr = [nums[i]];
        j = 0;
      }
    }
    return str;
  }
```
6. **Experience:**
  * 2002 – 2007  – teacher of mathematics and computer science in school;
  * 2008 – 2016 – software engineer JSC “GZLiN”;
  * 2016 – until now – software engineer JSC “Gomelstroymaterialy”.
7. **Professional achievements:**
	I developed  the following production projects, that were implemented in Visul FoxPro 9.0 environment, data was processed on SQL Server 2005 using the T-SQL language. I also managed the SQL Server 2005 databases:
  * for the sale of products of the enterprise to third-party customers (order formation, its inclusion in the general production plan, determination of its value);
  * for the formation of piecework wages of shop floor workers (pricing, separation of composite parts, payment calculation);
  * for the formation of tax reporting documents in XLM format.
8. **Education:**
  *	1997 – 2001 – “Loev State Pedagogical College”, specialty “Primary Education”;
  *	2002 – 2007 – “Mozyr State Pedagogical Uneversity named after “I.P.Shamyakin”, specialty “Mathematics and computer science” (in absentia);
  *	2007 – 2008 – “Republican Institute for Advanced Studies and Retraining of Employees of the Ministry of Labor and Social Protection of the Republic of Belarus”, specialty “Information systems software”;
  *	2017 – 2018 – courses: “English company” level: elementary.
9. **English:**
level – A1+, I practice with a tutor to improve my language skills.