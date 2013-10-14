# Additional translations at https://github.com/plataformatec/devise/wiki/I18n

en:
  devise:
    confirmations:
      confirmed: "A sua conta foi confirmada com sucesso. Está agora conectado."
      send_instructions: "Irá receber um email com instruções sobre como confirmar a sua conta dentro de alguns minutos."
      send_paranoid_instructions: "Se o seu email existir na nossa base de dados, irá receber uma mensagem com instruções sobre como confirmar a sua conta dentro de alguns minutos."
    failure:
      already_authenticated: "Já está conectado."
      inactive: "A sua conta ainda não foi ativada."
      invalid: "Email ou palavra-passe inválidos."
      invalid_token: "Token inválido."
      locked: "A sua conta está bloqueada."
      not_found_in_database: "Email ou palavra-passe inválidos."
      timeout: "A sua sessão expirou, por favor entre novamente para continuar."
      unauthenticated: "É necessário autenticar-se ou registar-se antes de continuar."
      unconfirmed: "É necessário confirmar a sua conta antes de continuar."
    mailer:
      confirmation_instructions:
        subject: "Instruções de confirmação"
      reset_password_instructions:
        subject: "Instruções para redefinir a palavra-passe"
      unlock_instructions:
        subject: "Instruções para Desbloquear"
    omniauth_callbacks:
      failure: "Não foi possível autenticá-lo com a conta %{kind} porque \"%{reason}\"."
      success: "Autenticação com sucesso com a conta %{kind}."
    passwords:
      no_token: "Não pode aceder a esta página sem ser a partir do email de redefinição de palavra-passe. Se aceder através do email de redefinição de palavra-passe, por favor certifique-se de que utilizou todo o URL fornecido."
      send_instructions: "Irá receber um email com instruções para redefinir a sua palavra-passe dentro de alguns minutos."
      send_paranoid_instructions: "Se o seu email existir na nossa base de dados, irá receber um link de recuperação de palavra-passe dentro de alguns minutos."
      updated: "A sua palavra-passe foi alterada com sucesso. Está agora conectado."
      updated_not_active: "A sua palavra-passe foi alterada com sucesso."
    registrations:
      destroyed: "Adeus! A sua conta foi desativada com sucesso. Esperamos vê-lo novamente em breve."
      signed_up: "Bem-vindo! Registou-se com sucesso."
      signed_up_but_inactive: "Registou-se com sucesso. No entanto, ainda não pode iniciar sessão por que a sua conta ainda não foi ativada."
      signed_up_but_locked: "Registou-se com sucesso. No entanto, ainda não pode iniciar sessão por que a sua conta está bloqueada."
      signed_up_but_unconfirmed: "Uma mensagem com o link de confirmação foi enviada para o seu email. Por favor, abra esse link para ativar a sua conta."
      update_needs_confirmation: "Atualizou a sua conta com sucesso, mas precisamos verificar o seu novo email. Por favor verifique a sua caixa de entrada e clique no link de confirmação para finalizar o processo de confirmação do seu novo email."
      updated: "Atualizou a sua conta com sucesso."
    sessions:
      signed_in: "Sessão iniciada com sucesso."
      signed_out: "Sessão terminada com sucesso."
    unlocks:
      send_instructions: "Irá receber um email com instruções sobre como desbloquear a sua conta dentro de alguns minutos."
      send_paranoid_instructions: "Se a sua conta existir, irá receber um email com instruções sobre como desbloquear a sua conta dentro de alguns minutos."
      unlocked: "A sua conta foi desbloqueada com sucesso. Inicie sessão para continuar."
  errors:
    messages:
      already_confirmed: "já foi confirmada, por favor tente novamente"
      confirmation_period_expired: "deve ser confirmada dentro de %{period}, tente novamente por favor"
      expired: "expirou, por favor solicite uma nova"
      not_found: "não encontrada"
      not_locked: "não foi bloqueada"
      not_saved:
        one: "1 erro impediu este %{resource} de ser guardado:"
        other: "%{count} erros impediram este %{resource} de ser guardado:"
        handlebars:
          one: "1 erro impediu este {{ resource }} de ser guardado:"
          other: "{{ count }} erros impediram este {{ resource }} de ser guardado:"
