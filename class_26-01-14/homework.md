# Simple conditionals

## Profitable Gamble

File `data.txt` contains three values: `prob` (double), `prize` (double), `pay` (double).
Compute whether `prob * prize > pay`. Write `Yes` to `result.txt` if the condition holds, otherwise write `No`.

### Examples

<table style="width: 100%">
  <thead>
    <tr>
      <th>data.txt</th>
      <th>result.txt</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        <pre><code>0.2 50 9</code></pre>
      </td>
      <td>
        <pre><code>Yes</code></pre>
      </td>
    </tr>
    <tr>
      <td>
        <pre><code>0.9 1 2</code></pre>
      </td>
      <td>
        <pre><code>No</code></pre>
      </td>
    </tr>
    <tr>
      <td>
        <pre><code>0.9 3 2</code></pre>
      </td>
      <td>
        <pre><code>Yes</code></pre>
      </td>
    </tr>
  </tbody>
</table>

## Two Makes Ten

File `data.txt` contains two integers: `a`, `b`.
Write `Yes` to `result.txt` if one of them is 10 or if `a + b` is 10; otherwise write `No`.

### Examples

<table style="width: 100%">
  <thead>
    <tr>
      <th>data.txt</th>
      <th>result.txt</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        <pre><code>9 10</code></pre>
      </td>
      <td>
        <pre><code>Yes</code></pre>
      </td>
    </tr>
    <tr>
      <td>
        <pre><code>9 9</code></pre>
      </td>
      <td>
        <pre><code>No</code></pre>
      </td>
    </tr>
    <tr>
      <td>
        <pre><code>1 9</code></pre>
      </td>
      <td>
        <pre><code>Yes</code></pre>
      </td>
    </tr>
  </tbody>
</table>

## Leap Year

File `data.txt` contains one integer: `year`.
Write `Yes` to `result.txt` if `year` is a leap year; otherwise write `No`.

Rules:
- A year is a leap year if it is divisible by 4;
- Except years divisible by 100 are not leap years;
- Except years divisible by 400 are leap years.

### Examples

<table style="width: 100%">
  <thead>
    <tr>
      <th>data.txt</th>
      <th>result.txt</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        <pre><code>1990</code></pre>
      </td>
      <td>
        <pre><code>No</code></pre>
      </td>
    </tr>
    <tr>
      <td>
        <pre><code>1924</code></pre>
      </td>
      <td>
        <pre><code>Yes</code></pre>
      </td>
    </tr>
    <tr>
      <td>
        <pre><code>2021</code></pre>
      </td>
      <td>
        <pre><code>No</code></pre>
      </td>
    </tr>
  </tbody>
</table>
