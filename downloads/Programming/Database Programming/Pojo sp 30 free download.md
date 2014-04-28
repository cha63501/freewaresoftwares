# Download: Pojo-sp 3.0

**Short description: **

## Call database Stored Procedures using POJO objects.

  
**Thumbshot: **![](http://www.freewarefiles.com/screenshot/nopic.gif)   
  
**Download link:** [Download Pojo-sp 3.0](http://freesoftwares.boysofts.com/Pojo-sp_program_68732.html)  
  

**Publisher's Description**  
  

If you have to call stored procedures on your applications you have to use the
standard JDBC API working with CallableStatement objects. But now you can use
a more simple and efficient solution that use annotated POJO classes and a
ProcedureManager instance. Designed from scratch the pojo-sp library is
offering the best object oriented solution to use stored procedures on your
applications by hiding the JDBC SQL programming artifacts. For each stored
procedure or function call you have to design an annotated POJO class, a Java
Bean class with annotations. The POJO class must be decorated with a
@StoredProcedure annotation and you have to specify the name of the stored
procedure or function that is mapped by your class. If the procedure or the
function is from an Oracle package you have to specify also the name of the
package: .

Next you have to specify if the entity you are calling is a procedure or a
function. This attribute is by default true for stored procedures and must be
set to false if the entity you are calling is a function. The difference
between a procedure and a function is that the function always has a return
value. Inside your POJO class you have to define the stored procedure
parameters call and to decorate the fields with @StoredProcedureParameter
annotation. You have to specify the index of the parameter starting with 1 for
the first parameter. The names of the parameters are not important because the
parameters are accessed by index not by names. If the entity is a function the
first parameter (index = 1) is always the return value. The next attribute is
the SQL type of the parameter. Here you have to be carefully because you are
just did a mapping of a SQL type to a Java type and this mapping must match.
The last parameter is the direction attribute for this parameter which can be
IN, OUT or INOUT. For a function result parameter you must specify always OUT
as a direction attribute.

The next step is to create a ProcedureManager instance, set the input
parameters on your POJO class and finally call the stored procedure. The
ProcedureManager instance is created using the
ProcedureManagerFactory.createInstance() method using a JBC Connection object
as parameter or a class decorated with @JDBC annotation. If you need to use
transactions a TransactionManager interface is available to use. Also all
AcheckedA exceptions are converted to AuncheckedA exceptions and itAs not
mandatory to use a try catch block on your code.

  
  
Screenshot: ![](http://www.freewarefiles.com/screenshot/nopic.gif)  
**For more freeware softwares visit [Freeware software downloads.](http://freesoftwares.boysofts.com/)**   
**And [Free softwares and php script downloads.](http://www.boysofts.com/)**

