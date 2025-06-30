<img src="images/logo.png" alt="KoncernBok logo" width="200" style="display: block; margin: 0 auto;">

# Webbaserat bokföringssystem med AI

**Bokföring.AI** är ett webbaserat bokföringsprogram utvecklat under flera kurser i min utbildning.  
Det är designat för koncernredovisning och hanterar flera bolag i samma system.

Backend: FastApi, SQLAlchemy

Databas: PostgreSQL

Frontend: React

Projektet integrerar tre AI-flöden för att automatisera ekonomiska processer:

✅ **Extrahering av fakturainformation från leverantörsfakturor**  
→ OCR och LLM tolkar PDF-fakturor och sparar data strukturerat i databasen.

✅ **Automatisk kontering av fakturarader**  
→ AI och vektordatabas föreslår konton baserat på tidigare bokföring.

✅ **AI-agent för frågor och verktygsanrop**  
→ Chatbaserad hjälp som kan svara på frågor eller anropa specifika verktyg via Orchestrator-agenter.

Nedan finns några bilder som visar olika delar av systemet. Klicka på dem för att förstora!

<h2>Bilder från projektet</h2>

<p align="center">
  <a href="images/start.png" target="_blank">
    <img src="images/start.png" alt="Skärm 1" width="300" style="margin:10px;">
  </a>
</p>

<h4>Manuell bokföring</h4>

<p align="center">
  <a href="images/manuall_journal_entry.png" target="_blank">
    <img src="images/manuall_journal_entry.png" alt="Skärm 1" width="200" style="margin:5px;">
  </a>
  <a href="images/list_transaktions.png" target="_blank">
    <img src="images/list_transaktions.png" alt="Skärm 1" width="200" style="margin:5px;">
  </a>
  <a href="images/list_transaktions_with_detail.png" target="_blank">
    <img src="images/list_transaktions_with_detail.png" alt="Skärm 1" width="200" style="margin:5px;">
  </a>
</p>

<h4>Fakturering</h4>

<p align="center">
  <a href="images/invoice_products.png" target="_blank">
    <img src="images/invoice_products.png" alt="Skärm 1" width="200" style="margin:5px;">
  </a>
  <a href="images/invioce_ready.png" target="_blank">
    <img src="images/invioce_ready.png" alt="Skärm 1" width="200" style="margin:5px;">
  </a>
  <a href="images/invoice_preview.png" target="_blank">
    <img src="images/invoice_preview.png" alt="Skärm 1" width="200" style="margin:5px;">
  </a>
</p>

<h4>Leverantörsfakturor</h4>

<p align="center">
  <a href="images/supplier_invoices_home.png" target="_blank">
    <img src="images/supplier_invoices_home.png" alt="Skärm 1" width="200" style="margin:5px;">
  </a>
  <a href="images/supplier_invoices_create_supplier.png" target="_blank">
    <img src="images/supplier_invoices_create_supplier.png" alt="Skärm 1" width="200" style="margin:5px;">
  </a>
    <a href="images/supplier_invoices_create_supplier.png" target="_blank">
    <img src="images/supplier_invoices_create_supplier.png" alt="Skärm 1" width="200" style="margin:5px;">
  </a>
  <a href="images/invoice_preview.png" target="_blank">
    <img src="images/invoice_preview.png" alt="Skärm 1" width="200" style="margin:5px;">
  </a>
</p>

<h4>Register</h4>

<p align="center">
  <a href="images/chart_of_accounts.png" target="_blank">
    <img src="images/chart_of_accounts.png" alt="Skärm 1" width="200" style="margin:5px;">
  </a>
  <a href="images/add_product.png" target="_blank">
    <img src="images/add_product.png" alt="Skärm 1" width="200" style="margin:5px;">
  </a>

</p>

<h4>Ai</h4>
<h6>Leverantörsfaktura, OCR tolkad av LLM utan RAG</h6>
<p align="center">
  </a>
    <a href="images/supplier_invoice_low_score_rag.png" target="_blank">
    <img src="images/supplier_invoice_low_score_rag.png" alt="Skärm 1" width="200" style="margin:5px;">
  </a>
  </p>

<h6>Leverantörsfaktura, OCR tolkad av LLM med RAG</h6>
  <p align="center">
      <a href="images/supplier_invoice_high_score_rag.png" target="_blank">
    <img src="images/supplier_invoice_high_score_rag.png" alt="Skärm 1" width="200" style="margin:5px;">
  </a>
</p>

<h6>Ai Assistent</h6>
  <p align="center">
      <a href="images/agent_with_tool_calling_through_mcp_sever.png" target="_blank">
    <img src="images/agent_with_tool_calling_through_mcp_sever.png" alt="Skärm 1" width="200" style="margin:5px;">
  </a>
    <a href="images/agent_question_1.png" target="_blank">
    <img src="images/agent_question_1.png" alt="Skärm 1" width="200" style="margin:5px;">
  </a>
      <a href="images/agent_history.png" target="_blank">
    <img src="images/agent_history.png" alt="Skärm 1" width="200" style="margin:5px;">
  </a>
</p>

<h6>Miro Databasstruktur</h6>

  <p align="center">
      <a href="images/postgreSQL_miro_structure.png" target="_blank">
    <img src="images/postgreSQL_miro_structure.png" alt="Skärm 1" width="200" style="margin:5px;">
  </a>
</p>

<h6>Qdrant Vektordatabas</h6>

  <p align="center">
      <a href="images/qdrant_vector_db_accounts_overview.png" target="_blank">
    <img src="images/qdrant_vector_db_accounts_overview.png" alt="Skärm 1" width="200" style="margin:5px;">
  </a>
        <a href="images/qdrant_vector_db_accounts_overview.png" target="_blank">
    <img src="images/qdrant_vector_db_accounts_overview.png" alt="Skärm 1" width="200" style="margin:5px;">
  </a>
</p>
