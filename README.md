## Phone porting status (all of which I own)

<table>
  <caption>PostmarketOS personal phone porting status</caption>
  <thead>      
      <th scope="col">Phone</th>
      <th scope="col">Porting status</th>
      <th scope="col">Details</th>
  </thead>
  <tbody>
    <tr>
      <th scope="row">LG G7 Thinq</th>
      <td>Already (somewhat) ported, working on the rest though</td>
      <td>Modem doesn't function correctly, display issues with panel driver.</td>
    </tr>
    <tr>
      <th scope="row">Motorola E4 (MSM8917 & MSM8920</th>
      <td>Ported, waiting on mainline.</td>
      <td>Modem doesn't function correctly, otherwise just about perfect.</td>
    </tr>
    <tr>
      <th scope="row">Moto G5 Plus</th>
      <td>Already ported</td>
      <td>Display issues with some panel variants that I happen to have</td>
    </tr>
    <tr>
      <th scope="row">Moto G7 Power</th>
      <td>Already (somewhat) ported</td>
      <td>Definitely alpha state, but not a priority because it already has maintainers.</td>
    </tr>
    <tr>
      <th scope="row">Motorola X Style</th>
      <td>Working on lk2nd port</td>
      <td>Quirky bootloader, haven't built up the guts to open it up for uart.</td>
    </tr>
    <tr>
      <th scope="row">Moto Droid Turbo 2</th>
      <td>No BL unlock.</td>
      <td>Going to try to blow the unlock fuse with firehorse.</td>
    </tr>
    <tr>
      <th scope="row">Samsung Galaxy A12</th>
      <td>Uniloader porting, can't boot linux yet</td>
      <td>MT6765 has no mainline support, though a working group is being formed.</td>
    </tr>
    <tr>
      <th scope="row">Samsung Galaxy J3 Emerge</th>
      <td>Ported, waiting on mainline.</td>
      <td>Has some major issues wrt to display reset sequence. Requires out of tree patches.</td>
    </tr>
    <tr>
      <th scope="row">Samsung Galaxy J7 Perx</th>
      <td>Ported, waiting on mainline.</td>
      <td>Has some major issues wrt to display reset sequence. Requires out of tree patches. No audio yet.</td>
    </tr>
    <tr>
      <th scope="row">Samsung Galaxy Note 1</th>
      <td>Boots into U-boot, but fails to start Linux.</td>
      <td>Already ported, working on BL situation.</td>
    </tr>
    <tr>
      <th scope="row">Samsung Galaxy Note 9 (Exynos)</th>
      <td>Thinking about it</td>
      <td>N/A</td>
    </tr>
    <tr>
      <th scope="row">Samsung Galaxy S6</th>
      <td>No BL unlock (yet)</td>
      <td>Waiting on time to port cadmium by chipmunkmc. Have done some trivial RE on S-Boot to look for exploits.</td>
    </tr>
  </tbody>
</table>

