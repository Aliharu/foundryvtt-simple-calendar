This section is used to configure how different aspects of Simple Calendar are displayed.

## Date/Time Formatting

![](media://calendar-display-options.png)

A date time format is text containing special tokens. These tokens are replaced with the corresponding date/time information to create a finalized display of that date and time. Below is a list of the different tokens available to use in Simple Calendar and what they do.

| Setting           | Description                                                                                                                          | Default       |
|-------------------|--------------------------------------------------------------------------------------------------------------------------------------|---------------|
| Date Format       | This format text is used when displaying a date anywhere in Simple Calendar                                                          | MMMM DD, YYYY |
| Time Format       | This format text is used when displaying a time anywhere in Simple Calendar                                                          | HH:mm:ss      |
| Month/Year Format | This format text is used when displaying just the month and year that appears at the top of a calendar view, above the list of days. | MMMM YAYYYYYZ |

Below are the tokens used in the above settings fields to configure the date and time to display how you want it to.

<table class="table table-striped table-bordered">
  <tbody>
    <tr>
      <th></th>
      <th>Token</th>
      <th>Description</th>
      <th>Example Results</th>
    </tr>
    <tr>
      <td><strong>Year</strong></td>
      <td>YY</td>
      <td>Year shorthand</td>
      <td>90 91 ... 19 20</td>
    </tr>
    <tr>
      <td></td>
      <td>YYYY</td>
      <td>Full year</td>
      <td>1990 1991 ... 2019 2020</td>
    </tr>
    <tr>
      <td></td>
      <td>YN</td>
      <td>Year name, as determined by the year name settings.</td>
      <td>Ral's Fury</td>
    </tr>
    <tr>
      <td></td>
      <td>YA</td>
      <td>Year prefix as defined in the Year Prefix setting.</td>
      <td>Pre</td>
    </tr>
    <tr>
      <td></td>
      <td>YZ</td>
      <td>Year postfix as defined in the Year Postfix setting.</td>
      <td>AD</td>
    </tr>
    <tr>
      <td><strong>Month</strong></td>
      <td>M</td>
      <td>Months number.</td>
      <td>1 2 ... 11 12</td>
    </tr>
    <tr>
      <td></td>
      <td>MM</td>
      <td>Months number padded with a zero.</td>
      <td>01 02 ... 11 12</td>
    </tr>
    <tr>
      <td></td>
      <td>MMM</td>
      <td>The months abbreviated name as defined in the months settings.</td>
      <td>Jan Feb ... Nov Dec</td>
    </tr>
    <tr>
      <td></td>
      <td>MMMM</td>
      <td>The months full name as defined in the months settings.</td>
      <td>January February ... November December</td>
    </tr>
    <tr>
      <td><strong>Day</strong></td>
      <td>D</td>
      <td>Day number.</td>
      <td>1 2 ... 30 31</td>
    </tr>
    <tr>
      <td></td>
      <td>DD</td>
      <td>Day number padded with a zero.</td>
      <td>01 02 ... 30 31</td>
    </tr>
    <tr>
      <td></td>
      <td>DO</td>
      <td>Day number appended with its suffix.</td>
      <td>1st 2nd ... 30th 31st</td>
    </tr>
    <tr>
      <td><strong>Weekday</strong></td>
      <td>d</td>
      <td>The number for the day of the week.</td>
      <td>1 2 ... 6 7</td>
    </tr>
    <tr>
      <td></td>
      <td>dd</td>
      <td>The number for the day of the week padded with a zero.</td>
      <td>01 02 ... 06 07</td>
    </tr>
    <tr>
      <td></td>
      <td>ddd</td>
      <td>The abbreviated name for the day of the week.</td>
      <td>Sun Mon ... Fri Sat</td>
    </tr>
    <tr>
      <td></td>
      <td>dddd</td>
      <td>The full name for the day of the week.</td>
      <td>Sunday Monday ... Friday Saturday</td>
    </tr>
    <tr>
      <td><strong>Hour</strong></td>
      <td>h</td>
      <td>The hours number in the 12 hour format.</td>
      <td>1 2 ... 11 12</td>
    </tr>
    <tr>
      <td></td>
      <td>H</td>
      <td>The hours number in the 24 hour format</td>
      <td>0 1 ... 22 23</td>
    </tr>
    <tr>
      <td></td>
      <td>hh</td>
      <td>The hours number padded with a zero in the 12 hour format.</td>
      <td>01 02 ... 11 12</td>
    </tr>
    <tr>
      <td></td>
      <td>HH</td>
      <td>The hours number padded with a zero in the 24 hour format.</td>
      <td>00 01 ... 22 23</td>
    </tr>
    <tr>
      <td></td>
      <td>a</td>
      <td>The am/pm indicator for the 12 hour time format in lowercase.</td>
      <td>am pm</td>
    </tr>
    <tr>
      <td></td>
      <td>A</td>
      <td>The AM/PM indicator for the 12 hour time format in uppercase.</td>
      <td>AM PM</td>
    </tr>
     <tr>
      <td><strong>Minute</strong></td>
      <td>m</td>
      <td>The minutes number.</td>
      <td>0 1 ... 58 59</td>
    </tr>
    <tr>
      <td></td>
      <td>mm</td>
      <td>The minutes number padded with a zero.</td>
      <td>00 01 ... 58 59</td>
    </tr>
    <tr>
      <td><strong>Second</strong></td>
      <td>s</td>
      <td>The seconds number.</td>
      <td>0 1 ... 58 59</td>
    </tr>
    <tr>
      <td></td>
      <td>ss</td>
      <td>The seconds number padded with a zero.</td>
      <td>00 01 ... 58 59</td>
    </tr>
    <tr>
      <td><strong>Text</strong></td>
      <td>[*]</td>
      <td> For any text that should be in the format but not processed place square brackets around it.</td>
      <td>[Don't process this text]</td>
    </tr>
  </tbody>
</table>

## Compact View Options

![](media://calendar-display-options-compact-view.png)

The [compact view](https://simplecalendar.info/pages/docs/using-sc/index/index.html#compact-view) has options to customize how it looks. These options are listed here:

| Setting                               | Description                                                                                                                                                                                                                                                                                                                                                                                                                             | Default       |
|---------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------|
| Compact View Date/Time Control Layout | Choose the layout for the buttons used to change the date/time of the calendar while in compact view.<br/>The options are:<ul><li>**Full Controls**: This display the full set of controls, the same that are available on the full calendar view.</li><li>**Quick Increment**: This layout offers 5 options (1 Round, 1 Minute, 5 Minutes, 15 Minutes, 1 Hour) and allows users to quickly advance the time by those amounts</li></ul> | Full Controls |

