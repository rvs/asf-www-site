Title: Board of Directors
license: https://www.apache.org/licenses/LICENSE-2.0

The [Board of Directors](../index.html#board-members) of The Apache Software Foundation (ASF) is responsible for
management and oversight of the business and affairs of the corporation in
accordance with the [Bylaws](../bylaws.html). This includes managing corporate assets (funds, intellectual property, trademarks, and support
equipment), appointing a President and corporate officers to manage
the core operations of the ASF, and allocating corporate resources for the benefit of Apache projects. 
Importantly, the ASF assigns [technical decision-making authority](../governance/#technical) for every
 Apache project the project's independent Project Management Committee (PMC). Participants in each project provide its direction, not the board.  
The [ASF membership](../members.html) elects to board annually.

Board meetings and minutes are published on the [board
calendar](calendar.html).  Many other [public records](../records/) of our 
corporation are publicly available.  Information about Apache [corporate governance and 
organization](../governance/) and [how board meetings work](meeting) are also available.

  {# This template is pre-processed using Django syntax #}
  {# If you wish to use the '{#' markdown id introducer, please use:  #} 
  {# '{% templatetag opencomment %}' instead of '{#'  #}
  {# see /lib/path.pm for further details #}

The current board of directors is:

  {% for bm in CI.board %}
-  {{ bm }}
  {% endfor %}

A listing of [all officers of the ASF][1] is also published, along with a
[history of past directors][2].


  [1]: http://www.apache.org/foundation/#who-runs-the-asf
  [2]: http://apache.org/history/directors.html