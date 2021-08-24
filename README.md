# markdown_test

## テーブルの書き方

### 普通の書き方

| TH | TH |
| --- | --- |
| TD | TD |
| TD | TD |

### 無理やりセルのマージを実現 (html)

<table>
  <thead>
    <tr>
      <th colspan="2">The table header</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>The table body</td>
      <td>with two columns</td>
    </tr>
    <tr>
      <td>The table body</td>
      <td>with two columns</td>
    </tr>
    <tr>
      <td>The table body</td>
      <td>with two columns</td>
    </tr>
  </tbody>
</table>


### テーブルのセル内で箇条書き (html)

<table>
  <thead>
    <th>name</th>
    <th>説明</th>
  </thead>
  <tbody>
    <tr>
      <td>1行目</td>
      <td>
        <ul>
          <li>1つめの項目</li>
          <li>2つめの項目</li>
          <li>3つめの項目</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td>2行目</td>
      <td>
        <ol>
          <li>1つめの項目</li>
          <li>2つめの項目</li>
          <li>3つめの項目</li>
        </ol>
      </td>
    </tr>
  </tbody>
</table>
