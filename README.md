rem-px-less-mixins
==================

REM to PX Mixins for LESS

Set baseline 
html {
  font-size: 62.5%;
}

Example 1:
USAGE
.padding-one-value(5)

OUTPUT
padding: 5px;
padding: 5rem;

Example 2:
USAGE
.padding-two-values(5,10);

OUTPUT
padding: 5px 10px;
padding: 5rem 10rem;

Example 3:
USAGE
.margin-three-values(5,10,15);

OUTPUT
margin: 5px 10px 15px;
margin: 5rem 10rem 15rem;

Example 4:
USAGE
.margin-four-values(5,10,15,20);

OUTPUT
margin: 5px 10px 15px 20px;
margin: 5rem 10rem 15rem 20rem;
