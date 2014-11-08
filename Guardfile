require 'guard/plugin'

module ::Guard
  class Inline < ::Guard::Plugin
    def start
      UI.info("Starting process")
    end

    def stop
      UI.info("Stopping process")
    end
  end
end

guard 'inline'
