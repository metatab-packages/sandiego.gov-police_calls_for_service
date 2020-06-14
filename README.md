# San Diego Police Calls For Service

This dataset links to the San Dieg Police Calls for Service datasets, from multiple years, combine the years and lints to the destriptions of disposition codes and beat neighborhoods. 

# Caveats and Adjustments

The meaning of the numbers in the `day_of_week` column has changed from earlier
to later years. Earlier years use values from 0 to 6, while later years use
vlaues from 1 to 7. Because of this, the `day_of_week` vlaues have been re-calculated to the span from 0 to 6, where 0 is Monday and 6 is Sunday. 
