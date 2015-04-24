user@TI-308:~$ R

R version 2.14.1 (2011-12-22)
Copyright (C) 2011 The R Foundation for Statistical Computing
ISBN 3-900051-07-0
Platform: i686-pc-linux-gnu (32-bit)

R is free software and comes with ABSOLUTELY NO WARRANTY.
You are welcome to redistribute it under certain conditions.
Type 'license()' or 'licence()' for distribution details.

  Natural language support but running in an English locale

R is a collaborative project with many contributors.
Type 'contributors()' for more information and
'citation()' on how to cite R or R packages in publications.

Type 'demo()' for some demos, 'help()' for on-line help, or
'help.start()' for an HTML browser interface to help.
Type 'q()' to quit R.

> C(22,33/ "rtu")
Error in C(22, 33/"rtu") : object not interpretable as a factor
> c ( 22,33, "rtu")
[1] "22"  "33"  "rtu"
> x<-c ( 22,33, "rtu")
> x
[1] "22"  "33"  "rtu"
> x[1]
[1] "22"
> as.
Display all 123 possibilities? (y or n)
as.array                       as.hclust
as.array.default               as.hexmode
as.call                        as.integer
as.character                   as.list
as.character.condition         as.list.data.frame
as.character.Date              as.list.Date
as.character.default           as.list.default
as.character.error             as.list.environment
as.character.factor            as.list.factor
as.character.hexmode           as.list.function
as.character.numeric_version   as.list.numeric_version
as.character.octmode           as.list.POSIXct
as.character.POSIXt            as.logical
as.character.srcref            as.logical.factor
as.complex                     as.matrix
as.data.frame                  as.matrix.data.frame
as.data.frame.array            as.matrix.default
as.data.frame.AsIs             as.matrix.noquote
as.data.frame.character        as.matrix.POSIXlt
as.data.frame.complex          as.name
as.data.frame.data.frame       as.null
as.data.frame.Date             as.null.default
as.data.frame.default          as.numeric
as.data.frame.difftime         as.numeric_version
as.data.frame.factor           as.octmode
as.data.frame.integer          as.ordered
as.data.frame.list             as.package_version
as.data.frame.logical          as.pairlist
as.data.frame.matrix           as.person
as.data.frame.model.matrix     as.personList
as.data.frame.numeric          as.POSIXct
as.data.frame.numeric_version  as.POSIXct.date
as.data.frame.ordered          as.POSIXct.Date
as.data.frame.POSIXct          as.POSIXct.dates
as.data.frame.POSIXlt          as.POSIXct.default
as.data.frame.raw              as.POSIXct.numeric
as.data.frame.table            as.POSIXct.POSIXlt
as.data.frame.ts               as.POSIXlt
as.data.frame.vector           as.POSIXlt.character
as.Date                        as.POSIXlt.date
as.Date.character              as.POSIXlt.Date
as.Date.date                   as.POSIXlt.dates
as.Date.dates                  as.POSIXlt.default
as.Date.default                as.POSIXlt.factor
as.Date.factor                 as.POSIXlt.numeric
as.Date.numeric                as.POSIXlt.POSIXct
as.Date.POSIXct                as.qr
as.Date.POSIXlt                as.raster
as.dendrogram                  as.raw
as.difftime                    as.real
as.dist                        as.relistable
as.double                      as.roman
as.double.difftime             as.single
as.double.POSIXlt              as.single.default
as.environment                 as.stepfun
as.expression                  as.symbol
as.expression.default          as.table
as.factor                      as.table.default
as.formula                     as.ts
as.function                    as.vector
as.function.default            as.vector.factor
as.graphicsAnnot               
> as.real(x[1])
[1] 22
> x[1]+3
Error in x[1] + 3 : non-numeric argument to binary operator
> as.real (x[1])+3
[1] 25
> as.real (x[3])+3
[1] NA
Warning message:
NAs introduced by coercion 
> as.real (x[2])+3
[1] 36
> rpois (1,2)
[1] 2
> 
> rpois (1,2)
[1] 0
> rpois (1,2)
[1] 5
> rpois (1,2)
[1] 2
> rpois (1,2)
[1] 3
> rpois (1,2)
[1] 0
> rpois (10,2)
 [1] 3 4 1 2 2 2 1 2 2 0
> rpois (10,2)
 [1] 3 2 2 2 2 3 0 2 3 5
> rpois (10,2)
 [1] 1 2 1 0 2 3 0 1 3 2
> rpois (10,2)
 [1] 1 2 3 3 3 4 6 0 2 3
> rpois (10,2)
 [1] 2 0 2 2 2 8 0 7 2 3
> rpois (10,2)
 [1] 2 2 4 4 2 1 3 1 2 2
> rpois (10,2)
 [1] 2 2 0 1 2 2 0 1 4 3
> rpois (10,2)
 [1] 1 3 5 1 2 1 2 3 0 2
> rpois (10,2)
 [1] 4 3 1 2 4 1 2 2 1 0
> rpois (10,2)
 [1] 3 5 1 2 2 1 1 3 4 1
> sum (rpois(10,2))
[1] 20
> sum (rpois(10,2))
[1] 24
> sum (rpois(10,2))
[1] 20
> sum (rpois(10,2))
[1] 15
> sum (rpois(10,2))
[1] 26
> sum (rpois(10,2))
[1] 23
> sum (rpois(10,2))
[1] 20
> sum (rpois(10,2))
[1] 22
> sum (rpois(10,2))
[1] 18
> sum (rpois(10,2))
[1] 25
> x <- rpois (10,2)
> x <- rpois (10,2)
> x
 [1] 2 3 1 4 2 2 3 2 1 1
> cumsum(x)
 [1]  2  5  6 10 12 14 17 19 20 21
> y <-cumsum (x)
> y
 [1]  2  5  6 10 12 14 17 19 20 21
> c(1:10)
 [1]  1  2  3  4  5  6  7  8  9 10
> t<-c(1:10)
> t
 [1]  1  2  3  4  5  6  7  8  9 10
> plot(t,y,"s")
> t<-(0:9)
> t
 [1] 0 1 2 3 4 5 6 7 8 9
> plot(t,y,"s")
> t<-(0:10)
> t
 [1]  0  1  2  3  4  5  6  7  8  9 10
> plot(t,y,"s")
Error in xy.coords(x, y, xlabel, ylabel, log) : 
  'x' and 'y' lengths differ
> y<-c(cumsum(x),max(x)
+ 
+ 
> y<-c(cumsum(x),max(x))
> t<-c(0:10)
> plot(t,y,"s")
> plot(t,y,"s",xlab="time",ylab="..",main="Arrival of clients")
> plot(t,y,"s",xlab="time",ylab="..",main="Arrival of clients"col="red")
Error: unexpected symbol in "plot(t,y,"s",xlab="time",ylab="..",main="Arrival of clients"col"
> plot(t,y,"s",xlab="time",ylab="..",main="Arrival of clients",col="red")
> plot(t,y,"s",xlab="time",ylab="..",main="Arrival of clients",col="red",lwd=3) 
> y
 [1]  2  5  6 10 12 14 17 19 20 21  4
> x
 [1] 2 3 1 4 2 2 3 2 1 1
> y<-c(cumsum(x),max(cumsum(x))
+ 
> y<-c(cumsum(x),max(cumsum(x)))
> y
 [1]  2  5  6 10 12 14 17 19 20 21 21
> plot(t,y,"s",xlab="time",ylab="..",main="Arrival of clients",col="red",lwd=3)
> 
