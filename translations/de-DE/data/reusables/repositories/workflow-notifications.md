Wenn Sie E-Mail- oder Webbenachrichtigungen für {% data variables.product.prodname_actions %} aktivieren, erhalten Sie eine Benachrichtigung, wenn ein von Ihnen ausgelöster Workflow abgeschlossen ist. Die Benachrichtigung enthält den Status der Workflow-Ausführung (einschließlich erfolgreicher, fehlgeschlagener, neutraler und abgebrochener Ausführungen). Sie können auch auswählen, ob Sie nur dann eine Benachrichtigung erhalten möchten, wenn eine Workflow-Ausführung fehlgeschlagen ist. For more information about enabling or disabling notifications, see "[About notifications](/account-and-profile/managing-subscriptions-and-notifications-on-github/setting-up-notifications/about-notifications)."

Notifications for scheduled workflows are sent to the user who initially created the workflow. If a different user updates the cron syntax in the workflow file, subsequent notifications will be sent to that user instead.{% ifversion fpt or ghes > 2.22 %} If a scheduled workflow is disabled and then re-enabled, notifications will be sent to the user who re-enabled the workflow rather than the user who last modified the cron syntax.{% endif %}

Du kannst den Status von Workflow-Ausführungen auch auf der Registerkarte „Actions“ (Aktionen) eines Repositorys einsehen. Weitere Informationen findest Du unter „[Eine Workflow-Ausführung verwalten](/actions/automating-your-workflow-with-github-actions/managing-a-workflow-run)."