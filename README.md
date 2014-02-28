drupal_development_tools_feature
================================

<h2> Instalation: </h2>
Clone this repository into your features directory.
Enable it with drush or by admin/modules path:
<code>drush en drupal_development_tools_feature</code>

<h2> Features: </h2>
<h3>Module dependencies:</h3>
<ul>
  <li>Devel</li>
  <li>Coder</li>
  <li>coder_review</li>
  <li>Features</li>
  <li>Fe_block</li>
  <li>strongarm</li>
  <li>CTools</li>
  <li>Coder</li>
</ul>

<h3>Basic configurations</h3>
<h4>Devel:</h4>
<ul>
  <li>
    <b>Permisions</b>
    <ul>
      <li>Access developer information: Anonymoous, authenticated</li>
      <li>Execute PHP code: None</li>
      <li>Switch users: authenticated</li>
    </ul>
  </li>
  <li>
    <b>Settings set:</b>
    <ul>
      <li>Display redirection page</li>
      <li>Display machine names of permissions and modules</li>
      <li>Error handlers : Standard Drupal</li>
      <li>Krumo display: Default</li>
    </ul>
  </li>
</ul>

<h4>Coder:</h4>
<b>Settings set:</b>
    <ul>
      <li>Checked : Drupal Coding Standards </li>
      <li>Checked : Drupal Commenting Standards</li>
      <li>Checked : Drupal SQL Standards</li>
      <li>Checked : Drupal Security Checks</li>
      <li>Checked : Internationalization</li>
      <li>Checked : Release standards</li>
      <li>Checked : include files (inc | php | install | test)</li>
    </ul>
<h3>Blocks:</h3>
<ul>
  <li>Switch user block (footer region)</li>
  <li>Development block (footer region)</li>
  <li>Execute PHP block (footer region)</li>
</ul>
