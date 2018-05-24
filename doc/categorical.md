## Categorical variable that suits official statistics needs

In statistical offices we often work with various classifications. The default
`factor` variable in R has only very limited capabilities. We could try to create
something better:

- Classifications often have codes and labels (think business classifications; regional classifications). It would be nice to keep those together and be able to switch between the two.
- Classifications are often hierarchical. Factors don't really allow for this. It would be nice of one would for example be able to switch between different levels. E.g. when aggregating. Perhaps this would also be of use for methods such as disclosure control.
- Translations. Be able to choose between different translations of categories, e.g. for internal and external output.

Concerning the hierarchical classifications: it would also be nice if
aggregates could be calculated at different levels as is the case in
statistical output tables. With tools such as dplyr this is now quite
cumbersome. Perhaps a different `group_by`.


