# Additional translations at https://github.com/plataformatec/devise/wiki/I18n

en:
  devise:
    confirmations:
      confirmed: "Your account was successfully confirmed. You are now signed in."
      send_instructions: "You will receive an email with instructions about how to confirm your account in a few minutes."
      send_paranoid_instructions: "If your email address exists in our database, you will receive an email with instructions about how to confirm your account in a few minutes."
    failure:
      already_authenticated: "You are already signed in."
      inactive: "Your account was not activated yet."
      invalid: "Invalid email or password."
      invalid_token: "Invalid authentication token."
      locked: "Your account is locked."
      not_found_in_database: "Invalid email or password."
      timeout: "Your session expired, please sign in again to continue."
      unauthenticated: "You need to sign in or sign up before continuing."
      unconfirmed: "You have to confirm your account before continuing."
    mailer:
      confirmation_instructions:
        subject: "Confirmation instructions"
      reset_password_instructions:
        subject: "Reset password instructions"
      unlock_instructions:
        subject: "Unlock Instructions"
    omniauth_callbacks:
      failure: "Could not authenticate you from %{kind} because \"%{reason}\"."
      success: "Successfully authenticated from %{kind} account."
    passwords:
      no_token: "You can't access this page without coming from a password reset email. If you do come from a password reset email, please make sure you used the full URL provided."
      send_instructions: "You will receive an email with instructions about how to reset your password in a few minutes."
      send_paranoid_instructions: "If your email address exists in our database, you will receive a password recovery link at your email address in a few minutes."
      updated: "Your password was changed successfully. You are now signed in."
      updated_not_active: "Your password was changed successfully."
    registrations:
      destroyed: "Bye! Your account was successfully cancelled. We hope to see you again soon."
      signed_up: "Welcome! You have signed up successfully."
      signed_up_but_inactive: "You have signed up successfully. However, we could not sign you in because your account is not yet activated."
      signed_up_but_locked: "You have signed up successfully. However, we could not sign you in because your account is locked."
      signed_up_but_unconfirmed: "A message with a confirmation link has been sent to your email address. Please open the link to activate your account."
      update_needs_confirmation: "You updated your account successfully, but we need to verify your new email address. Please check your email and click on the confirm link to finalize confirming your new email address."
      updated: "You updated your account successfully."
    sessions:
      signed_in: "Signed in successfully."
      signed_out: "Signed out successfully."
    unlocks:
      send_instructions: "You will receive an email with instructions about how to unlock your account in a few minutes."
      send_paranoid_instructions: "If your account exists, you will receive an email with instructions about how to unlock it in a few minutes."
      unlocked: "Your account has been unlocked successfully. Please sign in to continue."
  errors:
    messages:
      already_confirmed: "was already confirmed, please try signing in"
      confirmation_period_expired: "needs to be confirmed within %{period}, please request a new one"
      expired: "has expired, please request a new one"
      not_found: "not found"
      not_locked: "was not locked"
      not_saved:
        one: "1 error prohibited this %{resource} from being saved:"
        other: "%{count} errors prohibited this %{resource} from being saved:"
        handlebars:
          one: "1 error prohibited this {{ resource }} from being saved:"
          other: "{{ count }} errors prohibited this {{ resource }} from being saved:"
