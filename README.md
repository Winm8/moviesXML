# moviesXML

## Name
movies.xml
## Manual
### &lt;movies>
 * Main atribute
 * Parent to &lt;movie>
### &lt;movie>
 * Child to &lt;movies>
 * Used for adding movies to database
 * Atributes:
   * &lt;id> Identification for &lt;movie>
   * &lt;name> Name of the &lt;movie>
   * &lt;year> Release date of &lt;movie>
   * &lt;country> Creation place of &lt;movie>
   * &lt;genres> Genre of the &lt;movie>
### &lt;year>
 * Child to &lt;movie>
 * Time of release date
 ### &lt;country>
 * Place of the &lt;movies> creation
 * Child to &lt;movie>
 * Atributes:
   * &lt;id> Identificator of country
   * &lt;name> Name of country
### &lt;genres>
 * Child to &lt;movie>
 * Atributes:
   * &lt;id> Indetification of &lt;genres>
   * &lt;name> Name of &lt;genres>
