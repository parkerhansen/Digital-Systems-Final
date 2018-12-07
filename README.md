## <u>Digital Networks</u>
<p align="center"><img src="Network.jpg" height="360" width="640"></p>
<nav>
<ul>

<li><a href="Users.php">Users</a></li>
<li><a href="SearchDevices.php">Devices</a></li>
<li><a href="Providers.php">Providers</a></li>
<li><a href="SearchPackage.php">Packages</a></li>
<li><a href="SearchAccessLogs.php">Access Logs</a></li>
</ul>
</nav>

<table>
  <tr>
    <td>
      <form action="SearchDevices.php" method="post">
      <center><b><u>Insert/Delete a Device</u></b><br><br>
      Manufacturer: <input type="text" name="manufacturerNameEdit" required>
      Device Name: <input type="text" name="deviceNameEdit" required><br>
      Type: <input type="text" name="typeEdit"><br>
      Functionality: <input type="text" name="functionalityEdit"><br>
      When can you Access?: <select type="text" name="ruleEdit"><br>
        <option value="">--Chose a Access Rule--</option>
        <option value="Every Day">Everyday</option>
        <option value="Weekdays">Weekdays</option>
        <option value="Weekends">Weekends</option>
        <option value="Evenings">Evenings</option>
        <option value="Mornings">Mornings</option></select><br>
      <input type="submit" name="insertDevice" value="Insert">
      <input type="submit" name="modifyDevice" value="Modify Type">
      <input type="submit" name="deleteDevice" value="Delete">
      </center>
      </form>
    </td>

    <td>
    <center>
    <form action="SearchDevices.php" method="post">
      <input type="text" name="manufacturerName" placeholder="Manufacturer Name" required>
      <input type="text" name="deviceName" placeholder="Device Name" required>
      <input type="submit" name="searchDeviceName" value="Search">
    </form>

    <form action="SearchDevices.php" method="post">
      What devices does a user have access to?:<input type="text" name="ssn" placeholder="User SSN (XXX-XX-XXXX)" required>
      <input type="submit" name="searchSSN" value="Search">
    </form>

    <form action="SearchDevices.php" method="post">
      What devices does a role have access to?:<select type="text" name="role" required>
        <option value="AuthorizedUser">Authorized User</option>
        <option value="SecondaryUser">Secondary User</option>
      <input type="submit" name="searchRole" value="Search">
    </form>

    <form action="SearchDevices.php" method="post">
      Chose a Functionality<select type="text" name="valueToSearch" required>
        <option value="Thermostat">Thermostat</option>
        <option value="Internet Access">Internet Access</option>
        <option value="Phone">Phone</option>
        <option value="Camera">Camera</option>
        <option value="Watch">Watch</option>
        <option value="Activity Tracker">Activity Tracker</option>
        <option value="Refrigerator">Refrigerator</option>
        <option value="Computer">Computer</option>
        <input type="submit" name="searchFunction" value="Search">
    </form>

    <form action="SearchDevices.php" method="post">
      <input type="submit" name="showAllDevices" value="Show All">
    </form>
    </center>
    </td>
  </tr>
</table>
