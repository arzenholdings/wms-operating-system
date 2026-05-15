# WMS Architecture Topology

This topology shows how the WMS operating architecture fits together across strategy, version-controlled documentation, implementation tracking, CRM execution, shared tools, and business lanes.

The architecture is intentionally lightweight:

- Lucid provides the strategic customer journey framework.
- The WMS operating docs preserve the framework in GitHub.
- Linear tracks implementation work.
- GoHighLevel executes CRM, pipelines, workflows, forms, and calendars.
- Codex is the primary build and documentation operator.
- OpenClaw is used only when browser automation or complex task execution is needed.
- Each business lane can reuse the same lifecycle framework.

```mermaid
flowchart TB
    subgraph top["Top Layer"]
        ben["Ben / Executive Operator"]
        dashboard["Weekly Operator Dashboard"]
        linearOPE["Linear OPE Workspace"]
    end

    subgraph framework["Strategic Framework"]
        lucid["Lucid / Customer Journey Blueprint"]
        lifecycle["Reusable Lifecycle Framework<br/>Target -> Attract -> Capture -> Engage -> Offer -> Close -> Delivery -> Impress -> Multiply"]
    end

    subgraph operatingSystem["Version-Controlled Operating System"]
        github["GitHub repo<br/>wms-operating-system"]
        docs["WMS Operating Docs"]
        sops["SOP Documentation"]
        ghlMaps["GoHighLevel Maps"]
        linearPlans["Linear Plans / Templates"]
    end

    subgraph execution["Execution Systems"]
        linear["Linear<br/>Project / task execution"]
        ghl["GoHighLevel<br/>CRM, pipelines, workflows, forms, calendars"]
        codex["Codex<br/>Primary build / documentation operator"]
        openclaw["OpenClaw<br/>Escalation + browser automation"]
    end

    subgraph sharedTools["Shared System Tools"]
        ms365["Microsoft 365<br/>Domains, email, docs"]
        deploy["Vercel / GitHub<br/>Websites and app deployment"]
        marketplaces["Amazon / Walmart<br/>Marketplace channels"]
    end

    subgraph lanes["Business Lanes"]
        wms["WMS"]
        commerce["Arzen Commerce / ShopRite growth vehicle"]
        arzenLLC["Arzen LLC / Dragon Balm protected seller account"]
        kinetic["Kinetic Moto"]
        driver["Driver Network"]
        cannabis["Cannabis Ops"]
        proletariat["Proletariat admin / billing"]
    end

    ben --> dashboard
    dashboard --> linearOPE
    linearOPE --> linear

    lucid --> lifecycle
    lifecycle --> docs
    docs --> github
    sops --> github
    ghlMaps --> github
    linearPlans --> github

    github --> linear
    github --> ghl

    linear --> dashboard
    ghl --> dashboard

    codex --> docs
    codex --> github
    codex --> linear
    codex --> ghlMaps
    codex -. "Escalate only when browser automation or complex task execution is needed" .-> openclaw
    openclaw --> linear
    openclaw --> ghl
    openclaw --> deploy

    ghl --> wms
    ghl --> commerce
    ghl --> arzenLLC
    ghl --> kinetic
    ghl --> driver
    ghl --> cannabis
    ghl --> proletariat

    lifecycle --> wms
    lifecycle --> commerce
    lifecycle --> arzenLLC
    lifecycle --> kinetic
    lifecycle --> driver
    lifecycle --> cannabis
    lifecycle --> proletariat

    ms365 --> wms
    ms365 --> commerce
    ms365 --> arzenLLC
    ms365 --> kinetic
    ms365 --> driver
    ms365 --> cannabis
    ms365 --> proletariat

    deploy --> commerce
    deploy --> kinetic
    deploy --> driver
    deploy --> wms

    marketplaces --> commerce
    marketplaces --> arzenLLC
```

## Operating Flow

1. Lucid / Customer Journey Blueprint feeds the WMS operating docs.
2. WMS operating docs live in the GitHub repo.
3. Linear tracks implementation.
4. GoHighLevel executes CRM and customer lifecycle operations.
5. Codex updates docs, repos, and implementation issues.
6. OpenClaw is used only when browser automation or complex task execution is needed.
7. Each business lane can use the same lifecycle framework with lane-specific fields, offers, systems, and SOPs.

