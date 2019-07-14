# go-packages-awesome

### Utility library
- [PIE](https://github.com/elliotchance/pie) 
  - A utility library for dealing with slices that focuses on type safety and performance
- [go-keyring](https://github.com/zalando/go-keyring)
  - Cross-platform keyring interface for Go
- [go-humanize](https://github.com/dustin/go-humanize)
  - formatters for units to human friendly sizes
  
### UID generator
 <table>
    <thead>
      <tr>
        <th>Package</th>
        <th>Id</th>
        <th>Format</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td><a href="https://github.com/segmentio/ksuid">github.com/segmentio/ksuid</a></td>
        <td><b><code class="notion-code-inline">0pPKHjWprnVxGH7dEsAoXX2YQvU</code></b></td>
        <td>4 bytes of time (seconds) + 16 random bytes</td>
      </tr>
      <tr>
        <td><a href="https://github.com/rs/xid">github.com/rs/xid</a></td>
        <td><b><code class="notion-code-inline">b50vl5e54p1000fo3gh0</code></b></td>
        <td>4 bytes of time (seconds) + 3 byte machine id + 2 byte process id + 3 bytes random</td>
      </tr>
      <tr>
        <td><a href="https://github.com/kjk/betterguid">github.com/kjk/betterguid</a></td>
        <td><b><code class="notion-code-inline">-Kmdih_fs4ZZccpx2Hl1</code></b></td>
        <td>8 bytes of time (milliseconds) + 9 random bytes</td>
      </tr>
      <tr>
        <td><a href="https://github.com/sony/sonyflake">github.com/sony/sonyflake</a></td>
        <td><b><code class="notion-code-inline">20f8707d6000108</code></b></td>
        <td>~6 bytes of time (10 ms) + 1 byte sequence + 2 bytes machine id</td>
      </tr>
      <tr>
        <td><a href="https://github.com/oklog/ulid">github.com/oklog/ulid</a></td>
        <td><b><code class="notion-code-inline">01BJMVNPBBZC3E36FJTGVF0C4S</code></b></td>
        <td>6 bytes of time (milliseconds) + 8 bytes random</td>
      </tr>
      <tr>
        <td><a href="https://github.com/chilts/sid">github.com/chilts/sid</a></td>
        <td><b><code class="notion-code-inline">1JADkqpWxPx-4qaWY47~FqI</code></b></td>
        <td>8 bytes of time (ns) + 8 random bytes</td>
      </tr>
      <tr>
        <td><a  href="https://github.com/lithammer/shortuuid">https://github.com/lithammer/shortuuid</a></td>
        <td><code class="notion-code-inline">dwRQAc68PhHQh4BUnrNsoS</code></td>
        <td>UUIDv4 or v5, encoded in a more compact way</td>
      </tr>
      <tr>
        <td><a  href="https://github.com/satori/go.uuid">github.com/satori/go.uuid</a></td>
        <td><b><code class="notion-code-inline">5b52d72c-82b3-4f8e-beb5-437a974842c</code></b></td>
        <td>UUIDv4 from <a class="notion-link" href="http://tools.ietf.org/html/rfc4122">RFC 4112</a> for comparison</td>
      </tr>
      <tr>
        <td><a  href="https://github.com/google/uuid">https://github.com/google/uuid</a></td>
        <td><b><code class="notion-code-inline">c01d7cf6-ec3f-47f0-9556-a5d6e9009a43</code></b></td>
        <td>UUIDv4</td>
      </tr>
    </tbody>
  </table>
