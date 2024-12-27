# Project-Generating-Keywords-for-Search-Campaigns
In this project, I developed a targeted set of keywords for a digital marketing campaign focused on the sofas section of a budget-friendly online furniture retailer. The aim was to attract price-sensitive customers while avoiding luxury terms.

Tasks:

What keywords would help the client sell the listed products through search campaigns?

Save at least 60 unique keywords as a DataFrame called keywords_df and a CSV file called keywords.csv.
Both of these should contain four columns:
Ad Group: containing the product names
Keyword: containing the product and keyword combinations, combined in both directions (word + product, and product + word)
Campaign: with the value SEM_Sofas in every row
Criterion Type: with the value Exact in every row.

Imagine working for a digital marketing agency, and the agency is approached by a massive online furniture retailer. They want to test your skills at creating large campaigns for all of their website. You are tasked with creating a prototype set of keywords for search campaigns for their sofas section. The client says that they want you to generate keywords for the following products:

- sofas
- convertible sofas
- love seats
- recliners
- sofa beds

The client is a low-cost retailer, offering many promotions and discounts. You will need to focus on such keywords. You will also need to move away from luxury keywords and topics, as you are targeting price-sensitive customers. Because they are going to be tight on budget, it would be good to focus on a tightly targeted set of keywords and make sure they are all set to exact and phrase match.

Based on the brief above you will first need to generate a list of words, that together with the products given above would make for good keywords. Here are some examples:

- Products: sofas, recliners
- Words: buy, prices

The resulting keywords: 'buy sofas', 'sofas buy', 'buy recliners', 'recliners buy', 'prices sofas', 'sofas prices', 'prices recliners', 'recliners prices'.

As a final result, you want to have a DataFrame that looks like this:

<table>
<thead>
<tr>
<th>Campaign</th>
<th>Ad Group</th>
<th>Keyword</th>
<th>Criterion Type</th>
</tr>
</thead>
<tbody>
<tr>
<td>Campaign1</td>
<td>AdGroup_1</td>
<td>keyword 1a</td>
<td>Exact</td>
</tr>
<tr>
<td>Campaign1</td>
<td>AdGroup_1</td>
<td>keyword 1b</td>
<td>Exact</td>
</tr>
<tr>
<td>Campaign1</td>
<td>AdGroup_2</td>
<td>keyword 2a</td>
<td>Exact</td>
</tr>
</tbody>
</table>
