---
layout: post
title:  "Bootstrap Grid System"
date:   2017-09-01
tags:
  - bootstrap
  - html
  - css
description: "How to make a site responsive using the Bootstrap grid system."
excerpt_separator:  <!--more-->
---
Make a site responsive using the Bootstrap [grid system](https://getbootstrap.com/docs/3.3/css/#grid):


1. Make a **container**: `<div class="container"></div>`.

2. Add a **row**: `<div class="row"></div>`.

3. Define the column space for each box. There are **12 columns** in each row.


  This means you can make a row with 4 boxes like this:

    <div class="container">
        <div class="row">
            <div class="col-xs-12 col-sm-6 col-md-3">
                <div class="card">
                    <h3>Box 1</h3>
                </div>
            </div>
            <div class="col-xs-12 col-sm-6 col-md-3">
                <div class="card">
                    <h3>Box 2</h3>
                </div>
            </div>
            <div class="col-xs-12 col-sm-6 col-md-3">
                <div class="card">
                    <h3>Box 3</h3>
                </div>
            </div>
            <div class="col-xs-12 col-sm-6 col-md-3">
                <div class="card">
                    <h3>Box 4</h3>
                </div>
            </div>
        </div>
    </div>

The classes to set the column width are:


- **col-xs-12**: on an extra small screen device (phone) the column width will be equal to the row width, i.e. all boxes will be below one another in a single column.
![](https://d2mxuefqeaa7sj.cloudfront.net/s_DF3E6D2DF13A1AA1C63387C5F183F8D88C261ACC49255C9841C23B8F107E7FE6_1504274678701_Screenshot+2017-09-01+11.03.50.png)

- **col-sm-6**: on a small device (tablet) the column width will be 6, so there are 2 columns with 2 boxes each.
![](https://d2mxuefqeaa7sj.cloudfront.net/s_DF3E6D2DF13A1AA1C63387C5F183F8D88C261ACC49255C9841C23B8F107E7FE6_1504274703571_Screenshot+2017-09-01+11.04.02.png)

- **col-md-3**: on a medium device (laptop or desktop) the width will be 3, showing the boxes on a single row.
![](https://d2mxuefqeaa7sj.cloudfront.net/s_DF3E6D2DF13A1AA1C63387C5F183F8D88C261ACC49255C9841C23B8F107E7FE6_1504274718642_Screenshot+2017-09-01+11.04.10.png)


You can test this here: [https://codepen.io/buzzmeekz/full/mMvqey/](https://codepen.io/buzzmeekz/full/mMvqey/)

