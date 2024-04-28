# drupalTable
How to sort HTML table by default in desc mode

Code In Controller (to Drupal 10)
To sort by default on click by desc in table header use 'initial_click_sort' => 'desc'

    $header = array(
      array('data' => t('Number'), 'field' => 'tid', 'sort' => 'desc', 'initial_click_sort' => 'desc'),
      array('data' => t('Time'), 'field' => 'changed', 'initial_click_sort' => 'desc'),
      array('data' => t('Status'), 'field' => 'status'),
    );
