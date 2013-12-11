

From:                                         Toshmatov, Jon H

Sent:                                           Wednesday, December 11, 2013 2:00 PM

Importance:                            High

 

MySQL Data Types

CHAR
	

String (0 - 255)

VARCHAR
	

String (0 - 255)

TINYTEXT
	

String (0 - 255)

TEXT
	

String (0 - 65535)

BLOB
	

String (0 - 65535)

MEDIUMTEXT
	

String (0 - 16777215)

MEDIUMBLOB
	

String (0 - 16777215)

LONGTEXT
	

String (0 - 429496­7295)

LONGBLOB
	

String (0 - 429496­7295)

TINYINT x
	

Integer (-128 to 127)

SMALLINT x
	

Integer (-32768 to 32767)

MEDIUMINT x
	

Integer (-8388608 to 8388607)

INT x
	

Integer (-2147­483648 to 214748­3647)

BIGINT x
	

Integer (-9223­372­036­854­775808 to 922337­203­685­477­5807)

FLOAT
	

Decimal (precise to 23 digits)

DOUBLE
	

Decimal (24 to 53 digits)

DECIMAL
	

"­DOU­BLE­" stored as string

DATE
	

YYYY-MM-DD

DATETIME
	

YYYY-MM-DD HH:MM:SS

TIMESTAMP
	

YYYYMM­DDH­HMMSS

TIME
	

HH:MM:SS

ENUM
	

One of preset options

SET
	

Selection of preset options

Integers (marked x) that are "­UNS­IGN­ED" have the same range of values but start from 0 (i.e., an UNSIGNED TINYINT can have any value from 0 to 255).

MySQL Type Conversion

BINARY 'string'

CAST (expre­ssion AS datatype)

CONVERT (expre­ssion, datatype)

MySQL Grouping Functions

AVG
	

MAX

BIT_AND
	

STD

BIT_OR
	

STDDEV

COUNT
	

SUM

GROUP_­CONCAT
	

VARIANCE

MIN
	

 
	

MySQL Mathematical Functions

ABS
	

COS

SIGN
	

SIN

MOD
	

TAN

FLOOR
	

ACOS

CEILING
	

ASIN

ROUND
	

ATAN, ATAN2

DIV
	

COT

EXP
	

RAND

LN
	

LEAST

LOG, LOG2, LOG10
	

GREATEST

POW
	

DEGREES

POWER
	

RADIANS

SQRT
	

TRUNCATE

PI

MySQL String Functions

ASCII
	

MID

ORD
	

SUBSTR­ING­_INDEX

CONV
	

LTRIM

BIN,OC­T,HEX
	

RTRIM

CHAR
	

TRIM

CONCAT
	

SOUNDEX

CONCAT_WS
	

SPACE

LENGTH
	

REPLACE

CHAR_L­ENGTH
	

REPEAT

BIT_LENGTH
	

REVERSE

LOCATE
	

INSERT

INSTR
	

ELT

LPAD
	

FIELD

RPAD
	

LCASE

LEFT
	

UCASE

RIGHT
	

LOAD_FILE

SUBSTRING
	

QUOTE

 

 

 
PHP Array Functions

array_diff (arr1, arr2 ...)

array_­filter (arr, function)

array_flip (arr)

array_­int­ersect (arr1, arr2 ...)

array_­merge (arr1, arr2 ...)

array_pop (arr)

array_push (arr, var1, var2 ...)

array_­reverse (arr)

array_­search (needle, arr)

array_walk (arr, function)

count (count)

in_array (needle, haystack)
PHP String Functions

crypt (str, salt)

explode (sep, str)

implode (glue, arr)

nl2br (str)

sprintf (frmt, args)

strip_tags (str, allowe­d_tags)

str_re­place (search, replace, str)

strpos (str, needle)

strrev (str)

strstr (str, needle)

strtolower (str)

strtoupper (str)

substr (string, start, len)
PHP Filesystem Functions

clears­tat­cache ()

copy (source, dest)

fclose (handle)

fgets (handle, len)

file (file)

filemtime (file)

filesize (file)

file_e­xists (file)

fopen (file, mode)

fread (handle, len)

fwrite (handle, str)

readfile (file)
PHP Date and Time Functions

checkdate (month, day, year)

date (format, timestamp)

getdate (times­tamp)

mktime (hr, min, sec, month, day, yr)

strftime (forma­tst­ring, timestamp)

strtotime (str)

time ()
	

 
	
PHP Regular Expressions Functions

ereg (pattern, str)

split (pattern, str)

ereg_r­eplace (pattern, replace, str)

preg_grep (pattern, arr)

preg_match (pattern, str)

preg_m­atc­h_all (pattern, str, arr)

preg_r­eplace (pattern, replace, str)

preg_split (pattern, str)
Regular Expressions Syntax

^
	

Start of string

$
	

End of string

.
	

Any single character

(a|b)
	

a or b

(...)
	

Group section

[abc]
	

In range (a, b or c)

[^abc]
	

Not in range

\s
	

White space

a?
	

Zero or one of a

a*
	

Zero or more of a

a*?
	

Zero or more, ungreedy

a+
	

One or more of a

a+?
	

One or more, ungreedy

a{3}
	

Exactly 3 of a

a{3,}
	

3 or more of a

a{,6}
	

Up to 6 of a

a{3,6}
	

3 to 6 of a

a{3,6}?
	

3 to 6 of a, ungreedy

\
	

Escape character

[:punct:]
	

Any punctu­ation symbol

[:space:]
	

Any space character

[:blank:]
	

Space or tab

There's an excellent regular expression tester at: http:/­/re­gex­pal.com/
Pattern Modifiers

g
	

Global match

i *
	

Case-i­nse­nsitive

m *
	

Multiple lines

s *
	

Treat string as single line

x *
	

Allow comments and whitespace in pattern

e *
	

Evaluate replac­ement

U *
	

Ungreedy pattern

* PCRE modifier
	

 
	
PHP fopen() Modes

r
	

Read

r+
	

Read and write, prepend

w
	

Write, truncate

w+
	

Read and write, truncate

a
	

Write, append

a+
	

Read and write, append
PHP Date Formatting

Y
	

4 digit year (2008)

y
	

2 digit year (08)

F
	

Long month (January)

M
	

Short month (Jan)

m
	

Month ⁴ (01 to 12)

n
	

Month (1 to 12)

D
	

Short day name (Mon)

l
	

Long day name (Monday) (lowercase L)

d
	

Day ⁴ (01 to 31)

j
	

Day (1 to 31)

 

h
	

12 Hour ⁴ (01 to 12)

g
	

12 Hour (1 to 12)

H
	

24 Hour ⁴ (00 to 23)

G
	

24 Hour (0 to 23)

i
	

Minutes ⁴ (00 to 59)

s
	

Seconds ⁴ (00 to 59)

 

w
	

Day of week ¹ (0 to 6)

z
	

Day of year (0 to 365)

W
	

Week of year ² (1 to 53)

t
	

Days in month (28 to 31)

 

a
	

am or pm

A
	

AM or PM

B
	

Swatch Internet Time (000 to 999)

S
	

Ordinal Suffix (st, nd, rd, th)

 

T
	

Timezone of machine (GMT)

Z
	

Timezone offset (seconds)

O
	

GMT offset (hours) (+0200)

I
	

Daylight saving (1 or 0)

L
	

Leap year (1 or 0)

 

U
	

Seconds since Epoch ³

c
	

ISO 8601 (PHP 5) (2008-­07-­31T­18:­30:­13+­01:00)

r
	

RFC 2822 (Thu, 31 Jul 2008 18:30:13 +0100)

¹ 0 is Sunday, 6 is Saturday.
² Week that overlaps two years belongs to year that contains most days of that week. Hence week number for 1st January of a given year can be 53 if week belongs to previous year. date("W­", mktime(0, 0, 0, 12, 8, $year)) always gives correct number of weeks in $year.
³ The Epoch is the 1st January 1970.
⁴ With leading zeroes

 

 

 
mod_rewrite Tutorials

http:/­/ht­tpd.ap­ach­e.o­rg/­doc­s/c­urr­ent­/re­write/

http:/­/ww­w.a­dde­dby­tes.co­m/f­or-­beg­inn­ers­/ur­l-r­ewr­iti­ng-­for­-be­gin­ners/

http:/­/ne­t.t­uts­plu­s.c­om/­tut­ori­als­/ot­her­/a-­dee­per­-lo­ok-­at-­mod­_re­wri­te-­for­-ap­ache/
mod_rewrite RewriteRule Flags

C
	

Chained with next rule

CO=cookie
	

Set specified cookie

E=var:­value
	

Set enviro­nmental variable “var” to “value”

F
	

Forbidden (403 header)

G
	

Gone - no longer exists

H=handler
	

Set handler

L
	

Last - stop processing rules

N
	

Next - continue processing

NC
	

Case insens­itive

NE
	

Do not escape output

NS
	

Ignore if subrequest

P
	

Proxy

PT
	

Pass through

R[=code]
	

Redirect to new URL, with optional code (see below)

QSA
	

Append query string

S=x
	

Skip next x rules

T=mime­-type
	

Set mime type
mod_rewrite RewriteCond Flags

NC
	

Case insens­itive

OR
	

Combine with next rule using 'OR' instead of the default of 'AND'
Redirection Header Codes

301
	

Moved perman­ently

302
	

Moved tempor­arily (default)
mod_rewrite Directives

Rewrit­eEngine

Rewrit­eOp­tions

RewriteLog

Rewrit­eLo­gLevel

Rewrit­eLock

RewriteMap

Rewrit­eBase

Rewrit­eCond

Rewrit­eRule
	

 
	
Regular Expressions Syntax

^
	

Start of string

$
	

End of string

.
	

Any single character

(a|b)
	

a or b

(...)
	

Group section

[abc]
	

In range (a, b or c)

[^abc]
	

Not in range

\s
	

White space

a?
	

Zero or one of a

a*
	

Zero or more of a

a*?
	

Zero or more, ungreedy

a+
	

One or more of a

a+?
	

One or more, ungreedy

a{3}
	

Exactly 3 of a

a{3,}
	

3 or more of a

a{,6}
	

Up to 6 of a

a{3,6}
	

3 to 6 of a

a{3,6}?
	

3 to 6 of a, ungreedy

\
	

Escape character

[:punct:]
	

Any punctu­ation symbol

[:space:]
	

Any space character

[:blank:]
	

Space or tab

There's an excellent regular expression tester at: http:/­/re­gex­pal.com/
mod_rewrite Server Variables: HTTP Headers

%{HTTP­_US­ER_­AGENT}

%{HTTP­_RE­FERER}

%{HTTP­_CO­OKIE}

%{HTTP­_FO­RWA­RDED}

%{HTTP­_HOST}

%{HTTP­_PR­OXY­_CO­NNE­CTION}

%{HTTP­_AC­CEPT}
mod_rewrite Server Variables: Server Internals

%{DOCU­MEN­T_ROOT}

%{SERV­ER_­ADMIN}

%{SERV­ER_­NAME}

%{SERV­ER_­ADDR}

%{SERV­ER_­PORT}

%{SERV­ER_­PRO­TOCOL}

%{SERV­ER_­SOF­TWARE}
	

 

 
