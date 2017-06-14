---
id: model_II_boot_errors_table
shortdesc: List of the possible error messages you may encounter when using the [model_number] upon boot-up.
author: Wilson Rodriquez
---

# Model II Boot Errors Table

<table>
 <tr>
  <th>Error</th>
  <th>Message</th>
  <th>Explanation/Action</th>
 </tr>
 <tr>
  <td>BOOT ERROR CK</td>
  <td>Checksum error -- possibly a defective ROM.</td>
  <td>Contact RSSC.</td>
 </tr>
 <tr>
  <td>BOOT ERROR CT</td>
  <td>Defective CTC chip.</td>
  <td>Contact RSSC.</td>
 </tr>
 <tr>
  <td>BOOT ERROR DC</td>
  <td>Floppy disk controller error.<ol><li>Defective diskette.</li><li>Floppy disk expansion unit not on.</li><li>Defective FDC Chip or Drive.</li></ol></td>
  <td><ol><li>Try a different diskette.</li><li>Turn on the floppy disk expansion unit.</li><li>Contact RSSC.</li></ol></td>
 </tr>
 <tr>
  <td>BOOT ERROR DM</td>
  <td>DMA chip failure.</td>
  <td>DMA chip failure.</td>
 </tr>
 <tr>
  <td>BOOT ERROR D0 </td>
  <td>Drive not ready.<ol><li>Improperly inserted diskette.</li><li>Defective diskette.</li><li>Defective drive.</li></ol></td>
  <td><ol><li>Insert the diskette again and press .</li><li>Try a different diskette.</li><li>Contact RSSC.</li></ol></td>
 </tr>
 <tr>
  <td>BOOT ERROR HA </td>
  <td>Controller error. Aborted command: Problem during boot-up of hard disk.</td>
  <td>Re-initialize the hard disk or contact RSSC.</td>
 </tr>
 <tr>
  <td>BOOT ERROR HC</td>
  <td>CRC error. Invalid data in data field.</td>
  <td>Re-initialize the hard disk or contact RSSC.</td>
 </tr>
 <tr>
  <td>BOOT ERROR Z8</td>
  <td>Defective CPU.</td>
  <td>Contact RSSC.</td>
 </tr>
 <tr>
  <td>NOT A SYSTEM DISK</td>
  <td>Diskette in Drive 0 isn't a TRSDOS-II operating system diskette.</td>
  <td>Insert a TRSDOS-II operating system diskette into Drive 0.</td>
 </tr>
<!-- Note that there are more error messages, but this should be enough for demo purposes -->
</table>

RSSC = Radio Shack Service Center.