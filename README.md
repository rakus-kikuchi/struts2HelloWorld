HTTPステータス 500 – Internal Server Error
タイプ 例外報告

メッセージ Template not found for name "/template/shimple/text.ftl".

説明 サーバーは予期しない条件に遭遇しました。それはリクエストの実行を妨げます。

例外

org.apache.jasper.JasperException: Template not found for name "/template/shimple/text.ftl".
The name was interpreted by this TemplateLoader: org.apache.struts2.views.freemarker.FreemarkerThemeTemplateLoader@7bb5d1a6. - Class: freemarker.template.Configuration
File: Configuration.java
Method: getTemplate
Line: 2883 - freemarker/template/Configuration.java:2883:-1
	org.apache.jasper.servlet.JspServletWrapper.handleJspException(JspServletWrapper.java:618)
	org.apache.jasper.servlet.JspServletWrapper.service(JspServletWrapper.java:498)
	org.apache.jasper.servlet.JspServlet.serviceJspFile(JspServlet.java:383)
	org.apache.jasper.servlet.JspServlet.service(JspServlet.java:331)
	javax.servlet.http.HttpServlet.service(HttpServlet.java:583)
	org.apache.tomcat.websocket.server.WsFilter.doFilter(WsFilter.java:51)
	org.apache.struts2.dispatcher.filter.StrutsPrepareAndExecuteFilter.doFilter(StrutsPrepareAndExecuteFilter.java:138)
根本原因

Template not found for name "/template/shimple/text.ftl".
The name was interpreted by this TemplateLoader: org.apache.struts2.views.freemarker.FreemarkerThemeTemplateLoader@7bb5d1a6. - Class: freemarker.template.Configuration
File: Configuration.java
Method: getTemplate
Line: 2883 - freemarker/template/Configuration.java:2883:-1
	org.apache.struts2.components.UIBean.end(UIBean.java:541)
	org.apache.struts2.views.jsp.ComponentTagSupport.doEndTag(ComponentTagSupport.java:39)
	org.apache.jsp.index_jsp._jspx_meth_s_005ftextfield_005f0(index_jsp.java:223)
	org.apache.jsp.index_jsp._jspx_meth_s_005fform_005f0(index_jsp.java:182)
	org.apache.jsp.index_jsp._jspService(index_jsp.java:138)
	org.apache.jasper.runtime.HttpJspBase.service(HttpJspBase.java:70)
	javax.servlet.http.HttpServlet.service(HttpServlet.java:583)
	org.apache.jasper.servlet.JspServletWrapper.service(JspServletWrapper.java:465)
	org.apache.jasper.servlet.JspServlet.serviceJspFile(JspServlet.java:383)
	org.apache.jasper.servlet.JspServlet.service(JspServlet.java:331)
	javax.servlet.http.HttpServlet.service(HttpServlet.java:583)
	org.apache.tomcat.websocket.server.WsFilter.doFilter(WsFilter.java:51)
	org.apache.struts2.dispatcher.filter.StrutsPrepareAndExecuteFilter.doFilter(StrutsPrepareAndExecuteFilter.java:138)
根本原因

freemarker.template.TemplateNotFoundException: Template not found for name "/template/shimple/text.ftl".
The name was interpreted by this TemplateLoader: org.apache.struts2.views.freemarker.FreemarkerThemeTemplateLoader@7bb5d1a6.
	freemarker.template.Configuration.getTemplate(Configuration.java:2883)
	freemarker.template.Configuration.getTemplate(Configuration.java:2685)
	org.apache.struts2.components.template.FreemarkerTemplateEngine.renderTemplate(FreemarkerTemplateEngine.java:90)
	org.apache.struts2.components.UIBean.mergeTemplate(UIBean.java:580)
	org.apache.struts2.components.UIBean.end(UIBean.java:539)
	org.apache.struts2.views.jsp.ComponentTagSupport.doEndTag(ComponentTagSupport.java:39)
	org.apache.jsp.index_jsp._jspx_meth_s_005ftextfield_005f0(index_jsp.java:223)
	org.apache.jsp.index_jsp._jspx_meth_s_005fform_005f0(index_jsp.java:182)
	org.apache.jsp.index_jsp._jspService(index_jsp.java:138)
	org.apache.jasper.runtime.HttpJspBase.service(HttpJspBase.java:70)
	javax.servlet.http.HttpServlet.service(HttpServlet.java:583)
	org.apache.jasper.servlet.JspServletWrapper.service(JspServletWrapper.java:465)
	org.apache.jasper.servlet.JspServlet.serviceJspFile(JspServlet.java:383)
	org.apache.jasper.servlet.JspServlet.service(JspServlet.java:331)
	javax.servlet.http.HttpServlet.service(HttpServlet.java:583)
	org.apache.tomcat.websocket.server.WsFilter.doFilter(WsFilter.java:51)
	org.apache.struts2.dispatcher.filter.StrutsPrepareAndExecuteFilter.doFilter(StrutsPrepareAndExecuteFilter.java:138)
注意 原因のすべてのスタックトレースは、サーバのログに記録されています。
